<template>
  <section id="About">
    <div class="container">
      <div class="row">
        <div class="col-6">
          <p class="hover">Hover over me!</p>
          <p class="click">Click on me!</p>
          <img
            class="img-fluid"
            src="https://i.postimg.cc/j5xxw79g/Copy-of-Fatima-1.jpg"
            alt="Fatima"
          />
        </div>
        <div class="col-6">
          <h1 class="about-heading">About Me</h1>
          <p>
           I am introverted by nature, humble, dedicated, a good communicator, creative and passionate. I easily adapt to situations and most of all I am resilient. My intretests and hobbies include, but are not limited to; reading, hiking, wakeboarding and  playing sport. You can sometimes find me in my kitchen testing out new recipes.
          </p>
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Laudantium
            sint, molestias sequi modi quo, necessitatibus laborum animi debitis
            blanditiis quod dicta sapiente praesentium dolores eius reiciendis
            maxime magnam, eaque dignissimos.
          </p>
          <h2 class="skills-heading">Technical Skills</h2>
          <div class="container">
            <div class="row">
              <div class="card border-dark mb-3" style="max-width: 15rem">
                <div class="card-header text-dark">HTML</div>
                <div class="card-body text-dark">
                  <i class="fa-brands fa-html5" style="color: crimson"></i>
                </div>
              </div>
              <div class="card border-dark mb-3" style="max-width: 15rem">
                <div class="card-header text-dark">CSS</div>
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
                <div class="card-header text-dark">BOOTSTRAP</div>
                <div class="card-body text-dark">
                  <i class="fa-brands fa-bootstrap" style="color: purple"></i>
                </div>
              </div>
              <div class="card border-dark mb-3" style="max-width: 15rem">
                <div class="card-header text-dark">JAVASCRIPT</div>
                <div class="card-body text-dark">
                  <i class="fa-brands fa-js" style="color: yellow"></i>
                </div>
              </div>
            </div>
            <div class="row">
              <div class="card border-dark mb-3" style="max-width: 15rem">
                <div class="card-header text-dark">VUEJS</div>
                <div class="card-body text-dark">
                  <i
                    class="fa-brands fa-vuejs"
                    style="background-color: seagreen"
                  ></i>
                </div>
              </div>
              <div class="card border-dark mb-3" style="max-width: 15rem">
                <div class="card-header text-dark">MYSQL</div>
                <div class="card-body text-dark">
                  <i class="fa-solid fa-database"></i>
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
.fa-solid,
.fa-database {
  font-family: "Font Awesome 6 Brands";
  font-weight: 400;
  font-size: 5rem;
  display: flex;
  justify-content: center;
  align-items: center;
}

.hover {
  font-family: "Montserrat", sans-serif;
  font-size: 1rem;
  padding-top: 5rem;
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
  -webkit-transition: all 0.8s ease-in-out;
}

img:hover {
  filter: none;
  -webkit-filter: grayscale(0);
  -webkit-transform: scale(1.01);
}
</style>
