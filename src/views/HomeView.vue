<template>
  <section id="Landing">
    <h1>Fatima Galant <br /></h1>
    <div class="text-effect">
      <h2>Aspiring</h2>
      <br />
      <span>W</span>
      <span>E</span>
      <span>B</span>
      <br />
      <br />
      <span>D</span>
      <span>E</span>
      <span>V</span>
      <span>E</span>
      <span>L</span>
      <span>O</span>
      <span>P</span>
      <span>E</span>
      <span>R</span>
    </div>
    <Footer />
  </section>
  <section id="about"></section>
</template>

<script>
import Footer from "../components/Footer.vue";
export default {
  components: {
    Footer,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
* {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  scroll-behavior: smooth;
}
@import url('https://fonts.googleapis.com/css2?family=Poppins&family=Varela+Round&display=swap');
#Landing {
  background: linear-gradient(rgba(0, 0, 0, 0.288), rgba(0, 0, 0, 0.288)),
    url(https://i.postimg.cc/BQwrtsNf/emile-perron-xr-VDYZRGdw4-unsplash.jpg);
  background-size: cover;
  background-position: center;
  min-height: 100vh;
  color: white;
  display: flex;
  flex-direction: column;
  gap: 30px;
  font-size: 2rem;
  text-align: center;
}
@media screen and (max-width: 896px) {
  #Landing {
    height: 50%;
  }
}
h1 {
  color: white;
  font-size: 5rem;
  font-weight: 5rem;
font-family: 'Varela Round', sans-serif;
  padding-top: 6rem;
  display: flex;
  justify-content: center;
  text-shadow: 2px 2px rgba(0, 0, 0, 0.582);
}
h2 {
  font-weight: 4rem;
font-family: 'Varela Round', sans-serif;
  display: flex;
  justify-content: center;
  color: white;
  padding-bottom: 30px;
  text-shadow: 2px 2px 8px rgba(255 255 255 / 0.58);
}
span {
  animation: blinker 1s linear infinite;
}
#message:after {
  content: "";
  width: 3px;
  height: auto;
  background: black;
  position: absolute;
  animation: blink 1s infinite;
  margin-left: 5px;
}
@keyframes blinker {
  50% {
    opacity: 0;
  }
}

ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #000000;
}
.text-effect {
  color: #000;
  font-family: "Bitter", serif;
  font-size: 0;
  text-align: center;
  margin: 50px 0 0;
  padding-bottom: 333px;
}
.text-effect span {
  font-size: 28px;
  background-color: #fff;
  line-height: 100px;
  height: 100px;
  width: calc(100% / 12);
  box-shadow: 0 40px 50px rgba(0, 0, 0, 0.1);
  border: 1px solid #fff;
  display: inline-block;
  vertical-align: top;
  transition: all 0.3s ease;
}
.text-effect span:nth-child(odd) {
  animation: animate_1 1s ease-in-out infinite;
}
.text-effect span:nth-child(even) {
  animation: animate_2 1s ease-in-out infinite;
}
@keyframes animate_1 {
  0% {
    transform: skewY(0);
  }
  25% {
    transform: skewY(15deg);
  }
  50% {
    transform: skewY(0);
  }
  75% {
    transform: skewY(-15deg);
    background-color: #f9f9f9;
    color: rgb(34, 30, 30);
  }
  100% {
    transform: skewY(0);
  }
}
@keyframes animate_2 {
  0% {
    transform: skewY(0);
  }
  25% {
    transform: skewY(-15deg);
    background-color: #f9f9f9;
    color: rgb(34, 30, 30);
  }
  50% {
    transform: skewY(0);
  }
  75% {
    transform: skewY(15deg);
  }
  100% {
    transform: skewY(0);
  }
}
</style>
