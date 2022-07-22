<template>
  <section id="About" data-aos="fade-up">
    <div class="container">
      <div class="row">
        <div class="col-md-6 p-5">
          <p class="hover">Hover over me!</p>
          <p class="click">Click on me!</p>
          <img
            class="img-fluid"
            src="https://i.postimg.cc/j5xxw79g/Copy-of-Fatima-1.jpg"
            alt="Fatima"
          />
        </div>
        <div class="col-md-6 p-3">
          <h1 class="about-heading">About Me</h1>
          <p>
            Aspiring web developer with an affinity for continuous learning. I
            am introverted by nature, humble, dedicated, a good communicator,
            creative and passionate. I easily adapt to situations and most of
            all I am resilient. I love learning new things. My intretests and
            hobbies include, but are not limited to; reading, hiking,
            wakeboarding and playing sport. You can sometimes find me in my
            kitchen testing out new recipes.
          </p>
          <ul>
            <li>
              you can reach out to me via email :
              <a href="mailto:fatimagalant03@gmail.com"
                >fatimagalant03@gmail.com</a
              >
            </li>
            <li>or via phone : <a href="tel:0662091181">+27662091181</a></li>
            <li>
              connect with me on
              <a
                href="https://www.linkedin.com/in/fatima-g-778944228/"
                target="_blank"
                >Linkedin</a
              >
            </li>
          </ul>
          <h2 class="skills-heading p-3">Technical Skills</h2>
          <div class="container">
            <div class="row">
              <div class="card border-dark mb-3" style="max-width: 15rem">
                <div class="card-header text-dark">
                  <a
                    href="https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics#:~:text=HTML%20(HyperText%20Markup%20Language)%20is,using%20images%20and%20data%20tables."
                    target="_blank"
                    style="text-decoration: none; color: black"
                    >HTML</a
                  >
                </div>
                <div class="card-body text-dark">
                  <i class="fa-brands fa-html5" style="color: crimson"></i>
                </div>
              </div>
              <div class="card border-dark mb-3" style="max-width: 15rem">
                <div class="card-header text-dark">
                  <a
                    href="https://developer.mozilla.org/en-US/docs/Web/CSS"
                    target="_blank"
                    style="text-decoration: none; color: black"
                    >CSS</a
                  >
                </div>
                <div class="card-body text-dark">
                  <i
                    class="fa-brands fa-css3"
                    style="color: cornflowerblue"
                  ></i>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="card border-dark mb-3" style="max-width: 15rem">
                <div class="card-header text-dark">
                  <a
                    href="https://getbootstrap.com/"
                    target="_blank"
                    style="text-decoration: none; color: black"
                    class="tskills"
                    >BOOTSTRAP</a
                  >
                </div>
                <div class="card-body text-dark">
                  <i class="fa-brands fa-bootstrap" style="color: purple"></i>
                </div>
              </div>
              <div class="card border-dark mb-3" style="max-width: 15rem">
                <div class="card-header text-dark">
                  <a
                    href="https://www.javascript.com/"
                    target="_blank"
                    style="text-decoration: none; color: black"
                    class="tskills"
                    >JAVASCRIPT</a
                  >
                </div>
                <div class="card-body text-dark">
                  <i class="fa-brands fa-js" style="color: yellow"></i>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="card border-dark mb-3" style="max-width: 15rem">
                <div class="card-header text-dark">
                  <a
                    href="https://vuejs.org/"
                    target="_blank"
                    style="text-decoration: none; color: black"
                    class="tskills"
                    >VUEJS
                  </a>
                </div>
                <div class="card-body text-dark">
                  <i
                    class="fa-brands fa-vuejs"
                    style="background-color: white; color: seagreen"
                  ></i>
                </div>
              </div>
              <div class="card border-dark mb-3" style="max-width: 15rem">
                <div class="card-header text-dark">
                  <a
                    href="https://www.mysql.com/"
                    target="_blank"
                    style="text-decoration: none; color: black"
                    class="tskills"
                    >MYSQL
                  </a>
                </div>
                <div class="card-body text-dark">
                  <i
                    class="fa-solid fa-database"
                    style="
                      font-size: 5rem;
                      display: flex;
                      justify-content: center;
                      align-items: center;
                    "
                  ></i>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="card border-dark mb-3" style="max-width: 15rem">
                <div class="card-header text-dark">
                  <a
                    href="https://nodejs.org/"
                    target="_blank"
                    style="text-decoration: none; color: black"
                    class="tskills"
                    >NODEJS</a
                  >
                </div>
                <div class="card-body text-dark">
                  <i class="fa-brands fa-node" style="color: green"></i>
                </div>
              </div>
              <div class="card border-dark mb-3" style="max-width: 15rem">
                <div class="card-header text-dark">
                  <a
                    href="https://github.com/"
                    target="_blank"
                    style="text-decoration: none; color: black"
                    class="tskills"
                    >GITHUB</a
                  >
                </div>
                <div class="card-body text-dark">
                  <i class="fa-brands fa-github"></i>
                </div>
              </div>
            </div>
          </div>
          <!-- <div class="card border-dark mb-3" style="max-width: 18rem; d-flex">
  <div class="card-header text-dark">NODEJS</div>
  <div class="card-body text-dark">
    <i class="fa-brands fa-node-js"></i>
  </div>
</div> -->
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
};
</script>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@1,300&family=Noto+Sans+Mono:wght@200;300&family=Noto+Serif+Display:wght@700&family=Poppins:wght@200&display=swap");
#About {
  background-color: rgb(41, 41, 41) !important ;
  color: white;
  min-height: 100vh;
}
.about-heading {
  font-family: "Montserrat", sans-serif;
  font-weight: 2rem;
  font-size: 3rem;
  padding-top: 5rem;
}
.skills-heading {
  font-family: "Montserrat", sans-serif;
  font-size: 2rem;
  padding-top: 5rem;
}
.fa-brands,
.fab {
  font-family: "Font Awesome 6 Brands";
  font-weight: 400;
  font-size: 5rem;
  display: flex;
  justify-content: center;
  align-items: center;
}
#pin {
  font-size: 10px;
}
.hover {
  font-family: "Montserrat", sans-serif;
  font-size: 1rem;
  padding-top: 5rem;
}
a {
  color: cornflowerblue;
  /* text-decorations: none; */
}
.click {
  display: none;
}
@media screen and (max-width: 1300px) {
  .hover {
    display: none;
  }
  .click {
    display: block;
    font-family: "Montserrat", sans-serif;
    font-size: 1rem;
    padding-top: 5rem;
  }
}
.img-fluid {
  /* padding-top: 7rem; */
  padding-bottom: 5rem;
  filter: gray;
  -webkit-filter: grayscale(1);
}

img:hover {
  filter: none;
  -webkit-filter: grayscale(0);
  /* -webkit-transform: scale(1.01); */
}
.row {
  padding-bottom: 1rem;
}
.row[data-v-4cebd208] {
  padding-bottom: 1rem;
  padding-left: 31px;
}
/* .tskills:hover {
  color: blueviolet;
} */
</style>
