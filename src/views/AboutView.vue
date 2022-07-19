<template>
  <section id="About">
    <div class="container">
      <div id="about-card" class="card">
        <div class="row">
          <div class="col-6">
            <h2 class="Hover">Hover On Me!</h2>
            <h2 class="Click">Click On Me!</h2>
            <img
              class="img-fluid"
              src="https://i.postimg.cc/YC2S9Dvy/Copy-of-Fatima-1.jpg"
              alt="Fatima"
            />
          </div>
          <div class="col-6">
            <h2 class="header-2">About Me</h2>
            <p>
              hi Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Provident consectetur delectus sapiente placeat exercitationem
              voluptatibus vero? Reiciendis atque aut adipisci iusto
              exercitationem neque dolorum. Error, doloribus, autem vel animi
              saepe reiciendis cumque ea provident incidunt aut velit harum esse
              aspernatur?
            </p>
            <p>
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nostrum
              odio, sapiente expedita alias delectus earum! Quas, esse.
              Molestiae quia inventore totam cum, voluptates culpa soluta,
              facere expedita sunt ut fugiat.
            </p>
            <h3 class="Sskills">Soft Skills</h3>
            <ul>
              <li>Problem Solving</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section id="Skills">
    <h1>Technical Skills</h1>
    <div class="skills-container">
      <div class="row">
        <div class="col-sm-4 mt-3">
          <div id="skills-h" class="card">
            <i class="fa-brands fa-html5"></i>
          </div>
        </div>
        <div class="col-sm-4 mt-3">
          <div id="skills-c" class="card">
            <i class="fa-brands fa-css3"></i>
          </div>
        </div>
        <div class="col-sm-4 mt-3">
          <div id="skills-b" class="card">
            <i class="fa-brands fa-bootstrap"></i>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-sm-3 mt-3">
          <div id="skills-j" class="card"><i class="fa-brands fa-js"></i></div>
        </div>
        <div class="col-sm-3 mt-3">
          <div id="skills-v" class="card">
            <i class="fa-brands fa-vuejs"></i>
          </div>
        </div>
        <div class="col-sm-3 mt-3">
          <div id="skills-m" class="card">
            <i class="fa-solid fa-database"></i>
          </div>
        </div>
        <div class="col-sm-3 mt-3">
          <div id="skills-n" class="card">
            <i class="fa-brands fa-node-js"></i>
          </div>
        </div>
      </div>
    </div>
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
  padding-top: 6rem;
}
.header-2 {
  font-family: "Montserrat", sans-serif;
  font-size: 3rem;
}
.Hover {
  font-family: "Montserrat", sans-serif;
  padding-left: 5rem;
  font-size: 1rem;
}
#about-card {
  /* width: 50%; */
  padding: 10px;
  display: flex;
  justify-content: center;
  flex-direction: column;
  box-shadow: 3px 3px rgba(48, 48, 48, 0.226);
}
@media screen and (max-width: 802px) {
  p {
    font-family: "Poppins", sans-serif;
  }
}
.img-fluid {
  filter: gray;
  -webkit-filter: grayscale(1);
  -webkit-transition: all 0.8s ease-in-out;
  top: 2px;
  padding: 10px;
  width: 25rem;
  height: 30rem;
  aspect-ratio: 1;
  object-fit: cover;
}
@media screen and (max-width: 550px) {
  .img-fluid {
    filter: gray;
    -webkit-filter: grayscale(1);
    -webkit-transition: all 0.8s ease-in-out;
    top: 2px;
    padding: 10px;
    width: 12rem;
    height: 15rem;
    aspect-ratio: 1;
    object-fit: cover;
  }
}
.Click {
  display: none;
}
@media screen and (max-width: 1300px) {
  .Click {
    display: block;
    font-family: "Montserrat", sans-serif;
    padding-left: 5rem;
    font-size: 1rem;
  }
  .Hover {
    display: none;
  }
}
.img-fluid:hover {
  filter: none;
  -webkit-filter: grayscale(0);
  -webkit-transform: scale(1.01);
}
#Skills {
  padding: 20px;
  gap: 30px;
}
.Sskills {
  font-family: "Montserrat", sans-serif;
  font-size: 2rem;
}
h1 {
  font-family: "Montserrat", sans-serif;
  font-size: 3rem;
  display: flex;
  justify-content: center;
  border-radius: none !important;
}
.skills-container .card {
  box-shadow: 1px 1px 10px #6e8387;
  text-align: center;
  padding: 10%;
  width: fit-content;
}
#skills-h {
  width: 12rem;
  font-size: 9rem;
  padding: 20px;
  border-radius: 0 !important;
  box-shadow: 1px 1px black;
}
#skills-h:hover {
  width: 12rem;
  font-size: 10rem;
  padding: 20px;
  transition: 0.5s;
  background-color: rgb(158, 16, 44);
  color: white;
}
#skills-c {
  width: 12rem;
  font-size: 9rem;
  padding: 20px;
  border-radius: 0 !important;
  box-shadow: 1px 1px black;
}
#skills-c:hover {
  width: 12rem;
  font-size: 9rem;
  padding: 20px;
  transition: 0.5s;
  background-color: cornflowerblue;
  color: white;
}
#skills-b {
  width: 12rem;
  font-size: 9rem;
  padding: 20px;
  border-radius: 0 !important;
  box-shadow: 1px 1px black;
}
#skills-b:hover {
  width: 12rem;
  font-size: 10rem;
  padding: 20px;
  transition: 0.5s;
  background-color: blueviolet;
  color: white;
}
#skills-j {
  width: 12rem;
  font-size: 9rem;
  padding: 20px;
  border-radius: 0 !important;
  box-shadow: 1px 1px black;
}
#skills-j:hover {
  width: 12rem;
  font-size: 10rem;
  padding: 20px;
  transition: 0.5s;
  background-color: yellow;
  color: black;
}
#skills-v {
  width: 12rem;
  font-size: 9rem;
  padding: 20px;
  border-radius: 0 !important;
  box-shadow: 1px 1px black;
}
#skills-v:hover {
  width: 12rem;
  font-size: 10rem;
  padding: 20px;
  transition: 0.5s;
  background-color: seagreen;
}
#skills-m {
  width: 12rem;
  font-size: 9rem;
  padding: 20px;
  border-radius: 0 !important;
  box-shadow: 1px 1px black;
}
#skills-m:hover {
  width: 12rem;
  font-size: 10rem;
  padding: 20px;
  transition: 0.5s;
  background-color: black;
  color: white;
}
#skills-n {
  width: 12rem;
  font-size: 9rem;
  padding: 20px;
  border-radius: 0 !important;
  box-shadow: 1px 1px black;
}
#skills-n:hover {
  width: 12rem;
  font-size: 10rem;
  padding: 20px;
  transition: 0.5s;
  background-color: white;
  color: rgb(37, 114, 37);
}
</style>
