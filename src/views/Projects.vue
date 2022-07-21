<template>
  <section id="projects" class="bg-dark text-light">
    <h1>Projects</h1>
    <div v-for="project in projects" :key="project.id">
      <div class="container">
        <div class="row">
        <div class="box">
            <div class="imgBox">
               <a href="{{project.link}}">
                <img id="img" v-bind:src="project.imgURL"/> 
                </a>
            </div>
            <div class="content">
                <h2>{{project.title}} <br/>
                <span>{{project.category}}</span></h2>
                <a><i class="fa-brands fa-github"> "{{project.github}}"</i></a>
            </div>
        </div>
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
            link: "https://leschevresdigitalartgallery.netlify.app/",
            github:"https://github.com/fatimagalant/art-gallery"
        },
        {
          id: 2,
          category: "Javascript",
          title: "Property Listings",
          imgURL:
            "https://i.postimg.cc/T29F01hs/etienne-beauregard-riverin-B0a-Cv-AVSX8-E-unsplash.jpg",
          description:
            "This project was given to us to challenge our javascript skills and it  was an amazing opportunity to really put the skills that I've learnt to use.",
            link: "https://goldencrownproperties.netlify.app/",
            github:"https://github.com/fatimagalant/propertylisting"
        },
        {
          id: 3,
          category: "Bootstrap",
          title: "Personal Portfolio",
          imgURL:
            "https://i.postimg.cc/y89TfpvN/luca-bravo-9l-326-FISzk-unsplash.jpg",
          description:
            "During this project I put my html and css skills to use by creating a portfolio.",
            link:"https://fatimagalant.netlify.app/",
            github:"https://github.com/fatimagalant/final-portfolio"
        },
        {
          id: 4,
          category: "Javascript",
          title: "BMI Calculator",
          imgURL:
            "https://i.postimg.cc/WzkD2CDF/kenny-eliason-5dd-H9-Y2acc-I-unsplash.jpg",
          description:
            "This BMI Calculator was created using html for structure, css for styling and javascript for functionality.",
            link:"https://bmicalculatorfg.netlify.app/",
            gitub:"https://github.com/fatimagalant/bmi-calculator"
        },
        {
          id: 5,
          category: "Javascript",
          title: "Calculator",
          imgURL:
            "https://i.postimg.cc/pLGjxgkC/manik-roy-x-X6t-K3-F35f-M-unsplash.jpg",
          description:
            "When I had just learnt html and was introduced to css flexbox, I created the structure and styling using html and css. Later I came back and added functionality using javascript.",
            link:"https://flexboxcalculator.netlify.app/",
            gitub:"https://github.com/fatimagalant/calculator"
        },
        {
          id: 6,
          category: "Javascript",
          title: "To Do List",
          imgURL:
            "https://i.postimg.cc/4ysyp5Bn/thomas-bormans-pcps-Vsy-Fp-s-unsplash.jpg",
          description:
            "After just learning javascript, I was tasked (lol) to create a to do list.",
            link:"https://todolistfg.netlify.app/",
            github:"https://github.com/fatimagalant/to-do-list"
        },
        {
          id: 7,
          category: "Javascript",
          title: "Temperature Converter",
          imgURL:
            "https://i.postimg.cc/13wxZQ9h/jonas-jaeken-6-FCNk-B-z-M-o-unsplash.jpg",
          description:
            "This was one of the mini javascript projects I created to better my skills and continue practicing.",
            link:"https://temperatureconverterfg.netlify.app/",
            github:"https://github.com/fatimagalant/temperature-converter"
        },
        {
          id: 8,
          category: "Bootstrap",
          title: "Restaurant",
          imgURL:
            "https://i.postimg.cc/jj8YMhxL/igor-rand-wf-M1-Fi-k-Ma-Y-unsplash.jpg",
          description:
            "This is a restaurant inspired website that I created using bootstrap.",
            link:"https://restaurantlie.netlify.app/",
            githb:"https://github.com/fatimagalant/restaurant"
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
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500&display=swap");
*,
*::after,
*::before {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  font-size: 62.5%;
}

body {
  width: 100vw;
  min-height: 100vh;
  background-color: #f0f0f0;
  font-family: 'Poppins', sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
}

.container {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
}
#img{
  height: 30rem;
}
.container .box {
  position: relative;
  width: 30rem;
  height: 30rem;
  margin: 4rem;
}
@media screen and (max-width:1500px) {
.container .box {
  position: relative;
  width: 30rem;
  height: 30rem;
  margin: 4rem;
}
}

.container .box:hover .imgBox {
  transform: translate(-3.5rem, -3.5rem);
}

.container .box:hover .content {
  transform: translate(3.5rem, 3.5rem);
}

.imgBox {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 2;
  transition: all 0.5s ease-in-out;
}

.imgBox img {
  width: 30rem;
  height: 30rem;
  object-fit: cover;
  resize: both;
}

.content {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  padding: 1.5rem;
  display: flex;
  justify-content: center;
  background-color: rgb(53, 53, 53);
  z-index: 1;
  align-items: flex-end;
  text-align: center;
  transition: 0.5s ease-in-out;
}

.content h2 {
  display: block;
  font-size: 2rem;
  color: rgb(255, 255, 255);
  font-weight: 500;
  line-height: 2rem;
  letter-spacing: 1px;
}

.content span {
  color: #555;
  font-size: 1.4rem;
  font-weight: 300;
  letter-spacing: 2px;
}

@media (max-width: 600px) {
  .container .box:hover .content {
    transform: translate(0, 3.5rem);
  }
  .container .box:hover .imgBox {
    transform: translate(0, -3.5rem);
  }
}
</style>
