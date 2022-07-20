<template>
  <section id="item-view">
    <div id="item-wrapper">
      <div id="item-container" v-if="project">
        <div id="info-div">
          <p class="text-white artist-name">{{ project.title }}</p>
          <p id="image-description" class="text-white">
            " {{ project.description }} "
          </p>
        </div>
        <div class="d-flex flex-column align-items-start artist-name">
          <img id="artwork" v-bind:src="project.imgURL" alt="" />
          <p class="my-1 mt-3 text-white">{{ project.title }}</p>
          <p class="my-1 text-white">{{ project.category }}</p>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  // name: "artworkDetails",
  props: ["id"],
  computed: {
    project() {
      return this.$store.state.piece;
    },
  },
  mounted() {
    this.$store.dispatch("getSingleProject", this.id);
  },
};
</script>
