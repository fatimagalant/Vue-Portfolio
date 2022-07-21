<template>
  <section id="projects">
    <h1>Projects</h1>
    <div v-for="project in projects" :key="project.id">
      <div class="row">
        <div class="col">
          <img id="img" v-bind:src="project.imgURL" />
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  data() {
    return {
      projects: [
        {
          id: 1,
          category: "Vue",
          title: "Digital Art Gallery",
          imgURL:
            "https://i.postimg.cc/3x31WF3f/zalfa-imani-1xp5-Vxvy-KL0-unsplash.jpg",
          description:
            "This was a group project that was created by 3 other group members includig myself. I contributed the contact page, artists page and created the idea, as well as the extensive research and extra information needed to make this project complete",
        },
        {
          id: 2,
          category: "Javascript",
          title: "Property Listings",
          imgURL:
            "https://i.postimg.cc/T29F01hs/etienne-beauregard-riverin-B0a-Cv-AVSX8-E-unsplash.jpg",
          description:
            "This project was given to us to challenge our javascript skills and it  was an amazing opportunity to really put the skills that I've learnt to use.",
        },
        {
          id: 3,
          category: "Bootstrap",
          title: "Personal Portfolio",
          imgURL:
            "https://i.postimg.cc/y89TfpvN/luca-bravo-9l-326-FISzk-unsplash.jpg",
          description:
            "During this project I put my html and css skills to use by creating a portfolio.",
        },
        {
          id: 4,
          category: "Javascript",
          title: "BMI Calculator",
          imgURL:
            "https://i.postimg.cc/WzkD2CDF/kenny-eliason-5dd-H9-Y2acc-I-unsplash.jpg",
          description:
            "This BMI Calculator was created using html for structure, css for styling and javascript for functionality.",
        },
        {
          id: 5,
          category: "Javascript",
          title: "Calculator",
          imgURL:
            "https://i.postimg.cc/pLGjxgkC/manik-roy-x-X6t-K3-F35f-M-unsplash.jpg",
          description:
            "When I had just learnt html and was introduced to css flexbox, I created the structure and styling using html and css. Later I came back and added functionality using javascript.",
        },
        {
          id: 6,
          category: "Javascript",
          title: "To Do List",
          imgURL:
            "https://i.postimg.cc/4ysyp5Bn/thomas-bormans-pcps-Vsy-Fp-s-unsplash.jpg",
          description:
            "After just learning javascript, I was tasked (lol) to create a to do list.",
        },
        {
          id: 7,
          category: "Javascript",
          title: "Temperature Converter",
          imgURL:
            "https://i.postimg.cc/13wxZQ9h/jonas-jaeken-6-FCNk-B-z-M-o-unsplash.jpg",
          description:
            "This was one of the mini javascript projects I created to better my skills and continue practicing.",
        },
        {
          id: 8,
          category: "Bootstrap",
          title: "Restaurant",
          imgURL:
            "https://i.postimg.cc/jj8YMhxL/igor-rand-wf-M1-Fi-k-Ma-Y-unsplash.jpg",
          description:
            "This is a restaurant inspired website that I created using bootstrap.",
        },
      ],
    };
  },
};
</script>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@1,300&family=Noto+Sans+Mono:wght@200;300&family=Noto+Serif+Display:wght@700&family=Poppins:wght@200&display=swap");
#img {
  width: 500px;
  height: 600px;
  aspect-ratio: 1;
  object-fit: cover;
}
h1 {
  padding-top: 3rem;
  font-family: "Montserrat", sans-serif;
  text-align: center;
  font-size: 3rem;
}
</style>
