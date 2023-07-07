<template>
  <section id="resume" class="bg-dark test-light" data-aos="fade-up">
    <div
      class="container bg-dark aos-init aos-animate"
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
                  <h2 class="resume-title"><strong>Summary</strong></h2>
                  <hr>
                  <div class="resume-item pb-0">
                    <h4><strong>Fatima Galant</strong></h4>
                    <p>
                      <em
                        >I am Fatima Galant, a prospective full stack developer.
                        I'm 20 years old and reside in Cape Town, South
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
                  <h2 class="resume-title"><strong>Education</strong></h2>
                  <hr>
                  <div class="resume-item">
                    <h4><strong>Diploma Matric</strong></h4>
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
                    <h4><strong>Full Stack Web Development Bootcamp</strong></h4>
                    <h5>March 2022 - September 2022</h5>
                    <p><em> Life Choices Coding Academy </em></p>
                    <p>
                      I've studied at Life Choices Coding Academy, a 6 month
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
                  <h2 class="resume-title">
                    <strong>Professional Experience</strong>
                    <hr>
                  </h2>
                     <div class="resume-item">
                    <h4><strong>Software Developer Intern</strong></h4>
                    <h5>Jan 2023- June 2023 (6 Months)</h5>
                    <p><em>Code Infinity Pty Ltd, Cape Town (Remote) </em></p>
                    <ul>
                      <li>
                       Upskilling myself by learning PHP, React, Tailwind CSS and working on client projects using Wordpress & Elementor Pro .
                      </li>
                      <li>
                        Collaborated on a project with fellow interns where we developed a project for internal company use.  
                      </li>
                      <li>
                       Attended mandatory training sessions that helped me upskill in new languages and become exposed to different ways and better practices to code.
                      </li>
                    </ul>
                  </div>
                     <div class="resume-item">
                    <h4><strong>Web Developer Intern</strong></h4>
                    <h5>September 2022 - January 2023 (5 months)</h5>
                    <p><em>LC Studio, Cape Town (on-site)</em></p>
                    <ul>
                      <li>
                        Upskilling myself by learning Wordpress
                      </li>
                      <li>
                       and AWS Cloud Practitioning 
                      </li>
                      <li>
                       as well as working on personal projects using Wordpress (Elementor), and web applications using Vuetify, Quasar Framework. 
                      </li>
                    </ul>
                  </div>
                  <div class="resume-item">
                    <h4><strong>Volunteer</strong></h4>
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
  background-size: cover;
  background-position: center;
  min-height: 100vh;
  z-index: 100%;
font-family: 'Varela Round', sans-serif;
  font-weight: 200px;
  color: rgb(212, 212, 212);
}
.resume-item{
  margin-top: 20px;
    color: rgb(212, 212, 212);
}
h2.d-flex {
 font-family: 'Varela Round', sans-serif;
  font-weight: 5rem;
   font-size: 7rem;
     color: rgb(212, 212, 212);
}
h2.d-flex:after {
 font-family: 'Varela Round', sans-serif;
  font-weight: 5rem;
  content: "";
  display: block;
  width: 30px;
  height: 2px;
  background: #000;
  right: 0;
  top: 50%;
  position: absolute;
    color: rgb(212, 212, 212);
}
p.d-flex {
font-family: 'Poppins', sans-serif;
  font-weight: 10rem;
}
.resume-title {
font-family: 'Poppins', sans-serif;
  font-weight: 5rem;
    color: rgb(212, 212, 212);
}
h4 {
 font-family: 'Varela Round', sans-serif;
  font-weight: 6rem;
    color: rgb(212, 212, 212);
}
li {
font-family: 'Poppins', sans-serif;
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
hr{
 color: rgb(152, 152, 152);
}
</style>
