<template>
  <section id="About" data-aos="fade-up">
    <div class="container">
      <div class="row">
        <div class="col-md-4 p-5">
          <p class="hover">Hover over me!</p>
          <p class="click">Click on me!</p>
          <img
            class="img-fluid"
            src="https://i.postimg.cc/j5xxw79g/Copy-of-Fatima-1.jpg"
            alt="Fatima"
          />
        </div>
        <div class="col-md-8 p-5">
          <h1 class="about-heading">About Me</h1>
          <p>
           Summary:

Highly motivated and dedicated web developer with a strong passion for continuous learning and staying up-to-date with the latest industry trends. Proficient in a wide range of in-demand skills, including HTML5, CSS3, Bootstrap, JavaScript, Vue.js, MySQL, Node.js, Express.js, and WordPress using Elementor. Currently expanding expertise in PHP, React, Tailwind CSS, SASS, LESS, and Next.js. Committed to creating responsive and accessible web applications that showcase creativity and innovation. Adept at leveraging various technologies to build dynamic and engaging user experiences. Seeking opportunities to contribute to challenging projects and build a diverse portfolio of impressive web applications.
          </p>
          <ul class="pb-5">
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
            <div class="row p-5">
               <div class="col-md-2 p-1">
                  <i class="fa-brands fa-html5" style="color: crimson"></i>
                </div>
                     <div class="col-md-2 p-1">
                  <i
                    class="fa-brands fa-css3"
                    style="color: cornflowerblue"
                  ></i>
                     </div>
              <div class="col-md-2 p-1">
                  <i class="fa-brands fa-bootstrap" style="color: purple"></i>
              </div>
              <div class="col-md-2 p-1">
                  <i class="fa-brands fa-js" style="color: yellow"></i>
                </div>
                   <div class="col-md-2 p-1">
                  <i
                    class="fa-brands fa-vuejs"
                    style="color: seagreen"
                  ></i>
              </div>
                    <div class="col-md-2 p-1">
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
            <div class="row p-5">
                    <div class="col-md-2 p-1">
                  <i class="fa-brands fa-node" style="color: green"></i>
              </div>
                   <div class="col-md-2 p-1">
                  <i class="fa-brands fa-github"></i>
                </div>
                 <div class="col-md-2 p-1">
                  <i class="fa-brands fa-wordpress"></i>
                </div>
                 <div class="col-md-2 p-1">
                <i class="fa-brands fa-elementor" style="color: pink"></i>
                </div>
                 <div class="col-md-2 p-1">
              <i class="fa-brands fa-react" style="color:cornflowerblue;"></i>
                </div>
                 <div class="col-md-2 p-1">
             <i class="fa-brands fa-php" style="color:cornflowerblue;"></i>
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
  margin-top: 3rem;
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
  text-decoration: none;
  color: white;
}
a:hover {
  color: cornflowerblue;
  text-decoration: none;
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
  padding-bottom: 5rem;
  filter: gray;
  -webkit-filter: grayscale(1);
}

img:hover {
  filter: none;
  -webkit-filter: grayscale(0);
}
</style>
