<template>
  <section id="resume" class="bg-light">
    <div class="container aos-init aos-animate" data-aos="fade-up">
      <div class="section-title">
        <div class="intro">
          <div class="rotate"></div>
        </div>
        <h2 class="d-flex justify-content-center">Resume</h2>
        <p class="d-flex justify-content-center">
          Below you will find my education and experience which will be
          information of benefit to you to get to know about my professioal
          background.
        </p>
        <!-- <div id="resume-container" class="container mt-5 mb-5 container aos-init aos-animate" data-aos="fade-up"> -->
        <div class="container mt-5 mb-5">
          <div class="row">
            <div class="col-md-6">
              <ul class="timeline">
                <li>
                  <h3 class="resume-title">Summary</h3>
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
                  <h3 class="resume-title">Education</h3>
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
                  <h3 class="resume-title">Professional Experience</h3>
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
</template>
<style scoped>
#resume {
  background-color: white;
  background-size: cover;
  background-position: center;
  min-height: 100vh;
  z-index: 100%;
  font-family: "Karla", sans-serif;
  font-weight: 200px;
  padding-top: 9rem;
}
.heading {
  position: relative;
  font-size: 14px;
  padding-right: 20px;
  padding-left: 20px;
  text-transform: uppercase;
  transform: rotate(90deg);
}
.rotate .heading {
  font-family: "Karla", Arial, sans-serif;
  /* font-size: 14px; */
  text-transform: uppercase;
  letter-spacing: 1em;
  -webkit-transform: rotate(90deg);
  transform: rotate(90deg);
  -webkit-transform-origin: left top 0;
  transform-origin: left top 0;
  position: relative;
}
.rotate .heading:after {
  position: absolute;
  top: 8px;
  content: "";
  background: #000;
  width: 40px;
  height: 1px;
  margin: 2px;
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
  z-index: 400;
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
  border: 3px solid #14213d;
  left: 20px;
  width: 20px;
  height: 20px;
  z-index: 400;
}
.resume {
  background-color: #413620;
  padding-top: 100px;
}
#resume .container {
  border-radius: 5px;
  background-color: #f0f0f0;
  padding: 20px;
  height: fit-content;
}
</style>
