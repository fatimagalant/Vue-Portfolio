<template>
  <section id="projects" class="bg-dark text-light">
    <h1>Projects</h1>
    <p class="pb-5">Hover over my project cards!</p>
    <div class="row">
      <div
        v-for="project in projects"
        :key="project.id"
        class="col-md-6 pb-5 px-5"
      >
        <div class="flip-card">
          <div class="flip-card-inner">
            <div class="flip-card-front">
              <img id="img" v-bind:src="project.imgURL" alt="Avatar" />
            </div>
            <div class="flip-card-back">
              <h1>{{ project.title }}</h1>
              <p class="text-muted">{{ project.category }}</p>
              <p id="project-desc" class="p-2">{{ project.description }}</p>
              <div class="card-container">
                <div class="card m-1 p-3" id="social-card">
                  <div class="row">
                    <div class="col-6" id="col-github">
                      <a v-bind:href="project.github"
                        ><i class="fa-brands fa-github p-1" id="github"></i
                      ></a>
                    </div>
                    <div class="col-6" id="col-link">
                      <a v-bind:href="project.link"
                        ><i class="fa-solid fa-link p-1" id="link"></i>
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <Footer />
  </section>
</template>
<script>
import Footer from "../components/Footer.vue";
export default {
  components: {
    Footer,
  },

  data() {
    return {
      projects: [
        {
          id: 1,
          category: "Vue",
          title: " Art Gallery",
          imgURL:
            "https://i.postimg.cc/3x31WF3f/zalfa-imani-1xp5-Vxvy-KL0-unsplash.jpg",
          description:
            "This was a group project that was created by 3 other group members includig myself. I contributed the contact page, artists page and created the idea, as well as the extensive research and extra information needed to make this project complete",
          linkp: "Click on the image to see my project!",
          link: "https://leschevresdigitalartgallery.netlify.app/",
          github: "https://github.com/fatimagalant/art-gallery",
        },
        {
          id: 2,
          category: "Javascript",
          title: "Property Listings",
          imgURL:
            "https://i.postimg.cc/T29F01hs/etienne-beauregard-riverin-B0a-Cv-AVSX8-E-unsplash.jpg",
          description:
            "This project was given to us to challenge our javascript skills and it  was an amazing opportunity to really put the skills that I've learnt to use.",
          linkp: "Click on the image to see my project!",
          link: "https://goldencrownproperties.netlify.app/",
          github: "https://github.com/fatimagalant/propertylisting",
        },
        {
          id: 3,
          category: "Bootstrap",
          title: "Personal Portfolio",
          imgURL:
            "https://i.postimg.cc/y89TfpvN/luca-bravo-9l-326-FISzk-unsplash.jpg",
          description:
            "During this project I put my html and css skills to use by creating a portfolio.",
          linkp: "Click on the image to see my project!",
          link: "https://fatimagalant.netlify.app/",
          github: "https://github.com/fatimagalant/final-portfolio",
        },
        {
          id: 4,
          category: "Javascript",
          title: "BMI Calculator",
          imgURL:
            "https://i.postimg.cc/WzkD2CDF/kenny-eliason-5dd-H9-Y2acc-I-unsplash.jpg",
          description:
            "This BMI Calculator was created using html for structure, css for styling and javascript for functionality.",
          linkp: "Click on the image to see my project!",
          link: "https://bmicalculatorfg.netlify.app/",
          github: "https://github.com/fatimagalant/bmi-calculator",
        },
        {
          id: 5,
          category: "Javascript",
          title: "Calculator",
          imgURL:
            "https://i.postimg.cc/pLGjxgkC/manik-roy-x-X6t-K3-F35f-M-unsplash.jpg",
          description:
            "When I had just learnt html and was introduced to css flexbox, I created the structure and styling using html and css. Later I came back and added functionality using javascript.",
          linkp: "Click on the image to see my project!",
          link: "https://flexboxcalculator.netlify.app/",
          github: "https://github.com/fatimagalant/calculator",
        },
        {
          id: 6,
          category: "Javascript",
          title: "To Do List",
          imgURL:
            "https://i.postimg.cc/4ysyp5Bn/thomas-bormans-pcps-Vsy-Fp-s-unsplash.jpg",
          description:
            "After just learning javascript, I was tasked (lol) to create a to do list.",
          linkp: "Click on the image to see my project!",
          link: "https://todolistfg.netlify.app/",
          github: "https://github.com/fatimagalant/to-do-list",
        },
        {
          id: 7,
          category: "Javascript",
          title: "Temperature Converter",
          imgURL:
            "https://i.postimg.cc/13wxZQ9h/jonas-jaeken-6-FCNk-B-z-M-o-unsplash.jpg",
          description:
            "This was one of the mini javascript projects I created to better my skills and continue practicing.",
          linkp: "Click on the image to see my project!",
          link: "https://temperatureconverterfg.netlify.app/",
          github: "https://github.com/fatimagalant/temperature-converter",
        },
        {
          id: 8,
          category: "Bootstrap",
          title: "Restaurant",
          imgURL:
            "https://i.postimg.cc/jj8YMhxL/igor-rand-wf-M1-Fi-k-Ma-Y-unsplash.jpg",
          description:
            "This is a restaurant inspired website that I created using bootstrap.",
          linkp: "Click on the image to see my project!",
          link: "https://restaurantlie.netlify.app/",
          github: "https://github.com/fatimagalant/restaurant",
        },
      ],
    };
  },
};
</script>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@1,300&family=Noto+Sans+Mono:wght@200;300&family=Noto+Serif+Display:wght@700&family=Poppins:wght@200&display=swap");
@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.9.1/font/bootstrap-icons.css");
#img {
  width: 100%;
  height: 25rem;
  aspect-ratio: 1;
  object-fit: cover;
}

.card-container {
  display: flex;
  justify-content: center;
  margin-top: 2rem;
}
#col-github {
  display: flex;
  justify-content: flex-end;
}
#col-link {
  display: flex;
  justify-content: flex-start;
}
#social-card {
  background: transparent;
  border: none;
  box-shadow: 2px 2px 10px black;
  border-radius: 0rem;
  width: fit-content;
}
#github {
  color: black;
  font-size: 2rem;
}
#link {
  color: black;
  font-size: 2rem;
}
h1 {
  padding-top: 3rem;
  font-family: "Montserrat", sans-serif;
  text-align: center;
  font-size: 3rem;
}
h2 {
  padding-top: 3rem;
  font-family: "Montserrat", sans-serif;
  text-align: center;
  font-size: 3rem;
}
p {
  display: flex;
  justify-content: center;
  font-family: "Poppins", sans-serif;
}

*,
*::after,
*::before {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.flip-card {
  background-color: transparent;
  width: 100%;
  height: 25rem;
  perspective: 1000px;
}

.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.6s;
  transform-style: preserve-3d;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}

.flip-card-front,
.flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}

.flip-card-front {
  background-color: #bbb;
  color: black;
}

.flip-card-back {
  background-color: #696969;
  color: white;
  transform: rotateY(180deg);
}
@media only screen and (max-width: 600px) {
  h1 {
    padding-top: 2rem;
    font-family: "Montserrat", sans-serif;
    text-align: center;
    font-size: 2rem;
  }
  #project-desc {
    font-size: 0.9rem;
  }
}
</style>
