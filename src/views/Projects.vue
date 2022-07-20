<template>
  <section id="projects">
    <div class="container" id="box-container" v-if="projects">
      <div class="box" v-for="project in projects" :key="project.id">
        <img class="art-image" v-bind:src="project.imgURL" alt="" />
        <div id="text">
          <h3 class="pt-1 text-white" id="title">{{ project.title }}</h3>
          <p class="lead text-muted" id="address"></p>
          <p id="category">{{ project.description }}</p>
          <p id="description" class="py-4">
            {{ project.category }}
          </p>
          <router-link
            id="project-link"
            :to="{ name: 'projectDetails', params: { id: project.id } }"
            >More info <i class="bi bi-arrow-right"></i
          ></router-link>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  mounted() {
    this.$store.dispatch("getAllProjects");
  },
  computed: {
    projects() {
      if (this.$route.params.cat) {
        return this.$store.state.projects?.filter(
          (project) => project.category === this.$route.params.cat
        );
      }
      return this.$store.state.project;
    },
  },
};
</script>
<style></style>
