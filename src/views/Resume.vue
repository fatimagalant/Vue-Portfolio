<template>
  <section id="resume" class="bg-dark test-light" data-aos="fade-up">
    <div
      class="container bg-dark text-light aos-init aos-animate"
      data-aos="fade-up"
    >
      <div class="section-title">
        <div class="intro">
          <div class="rotate"></div>
        </div>
        <h2 class="d-flex justify-content-center">Resume</h2>
        <p class="d-flex justify-content-center">
          Below you will find my education and experience which will be
          information of benefit to you to get to know about my professional
          background.
        </p>
        <div class="container bg-dark text-light mt-5 mb-5">
          <div class="row">
            <div class="col-md-6">
              <ul class="timeline">
                <li>
                  <h3 class="resume-title"><strong>Summary</strong></h3>
                  <div class="resume-item pb-0">
                    <h4>Fatima Galant</h4>
                    <p>
                      <em
                        >I am Fatima Galant, a prospective full stack developer.
                        I'm 19 years old and reside in Cape Town, South
                        Africa.</em
                      >
                    </p>
                    <ul>
                      <li>Southern Suburbs, Cape Town, SA</li>
                      <li>+27 66 209 1181</li>
                      <li>fatimagalant03@gmail.com</li>
                    </ul>
                  </div>
                </li>
                <li>
                  <h3 class="resume-title"><strong>Education</strong></h3>
                  <div class="resume-item">
                    <h4>Diploma Matric</h4>
                    <h5>January 2021- December 2021</h5>
                    <p>
                      <em>Futures Academy</em>
                    </p>
                    <p>
                      I attended Futures Academy, an online-high school for my
                      matric year and graduated with a Bachelors pass.
                    </p>
                  </div>
                  <div class="resume-item">
                    <h4>Full Stack Web Development Bootcamp</h4>
                    <h5>March 2022-Present</h5>
                    <p><em> Life Choices Coding Academy </em></p>
                    <p>
                      I'm currently at Life Choices Coding Academy, a 12 month
                      coding bootcamp which is teaching me full stack web
                      development essential skills. I have built and will
                      continue building many projects with the skills I have
                      acquired.
                    </p>
                  </div>
                </li>
              </ul>
            </div>
            <div class="col-md-6">
              <ul class="timeline">
                <li>
                  <h3 class="resume-title">
                    <strong>Professional Experience</strong>
                  </h3>
                  <div class="resume-item">
                    <h4>Web Developer Intern</h4>
                    <h5>Sep 2022-Jan 2022 (5 months)</h5>
                    <p><em>LC Studio , Cape Town</em></p>
                    <ul>
                      <li>
                        My core objectives at LC Studio include upskilling myself, using the technologies I am learning to create personal projects and to work on client projects when I am proficient in Wordpress and PHP.
                      </li>
                    </ul>
                  </div>
                  <div class="resume-item">
                    <h4> Intern</h4>
                    <h5>Jan 2023-Present</h5>
                    <p><em>ode Infinity , Cape Town</em></p>
                    <ul>
                      <li>
                        My core objectives at ode Infinity include upskilling myself, using the technologies I am learning to create personal projects and to work on client projects when I am proficient.
                      </li>
                    </ul>
                  </div>
                  <div class="resume-item">
                    <h4>Volunteer</h4>
                    <h5>2014-2018</h5>
                    <p><em>Beitul Aman - Wynberg, Cape Town </em></p>
                    <ul>
                      <li>
                        The duties assigned to me included setting up, helping
                        with and serving food.
                      </li>
                      <li>
                        Attending to minor needs and wants of the residents.
                      </li>
                      <li>
                        Spending copious amounts of time entertaining them with
                        games of chess and other forms of entertainment.
                      </li>
                    </ul>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <Footer />
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
#resume {
  background-color: white;
  background-size: cover;
  background-position: center;
  min-height: 100vh;
  z-index: 100%;
  font-family: "Karla", sans-serif;
  font-weight: 200px;
  /* padding-top: 9rem; */
}
h2.d-flex {
  font-family: "Montserrat", sans-serif;
  font-weight: 5rem;
}
p.d-flex {
  font-family: "Poppins", sans-serif;
  font-weight: 10rem;
}
.resume-title {
  font-family: "Montserrat", sans-serif;
  font-weight: 5rem;
}
h4 {
  font-family: "Montserrat", sans-serif;
  font-weight: 6rem;
}
li {
  font-family: "Poppins", sans-serif;
}
ul.timeline {
  list-style-type: none;
  position: relative;
}
ul.timeline:before {
  content: " ";
  background: #000;
  display: inline-block;
  position: absolute;
  left: 29px;
  width: 2px;
  height: 100%;
  z-index: 1;
}
ul.timeline > li {
  margin: 20px 0;
  padding-left: 20px;
}
ul.timeline > li:before {
  content: " ";
  background: #000;
  display: inline-block;
  position: absolute;
  border-radius: 50%;
  border: 3px solid #000000;
  left: 20px;
  width: 20px;
  height: 20px;
  z-index: 400;
}
.resume {
  background-color: #c2b395;
  padding-top: 100px;
}
#resume .container {
  border-radius: 5px;
  background-color: #f0f0f0;
  padding: 20px;
  height: fit-content;
}
</style>
