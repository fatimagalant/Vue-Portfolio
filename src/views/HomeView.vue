<template>
  <section id="Landing">
    <h1>
      Fatima Galant <br />
    </h1>
<p id="message">
</p>
  </section>
  <section id="about"></section>
</template>

<script>
// import Footer from "../components/Footer.vue";
// export default {
//   components: {
//     Footer,
//   },
// };

let quoteArray = ["I am an aspiring fullstack developer"];
let textPosition = 0;
let speed = 100;
typewriter = () => {
  document.querySelector("#message").innerHTML =
    quoteArray[0].substring(0, textPosition) + "<span>\u25AE</span>";

  if (textPosition++ != quoteArray[0].length) setTimeout(typewriter, speed);
};
window.addEventListener("load", typewriter);
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
* {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  scroll-behavior: smooth;
}
@import url("https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@1,300&family=Noto+Sans+Mono:wght@200;300&family=Noto+Serif+Display:wght@700&family=Poppins:wght@200&display=swap");
#Landing {
  background: linear-gradient(rgba(0, 0, 0, 0.288), rgba(0, 0, 0, 0.288)),
    url(https://i.postimg.cc/BQwrtsNf/emile-perron-xr-VDYZRGdw4-unsplash.jpg);
 background-size: cover;
  background-position: center;
  min-height: 100vh;
  color: white;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
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
  font-family: "Montserrat", sans-serif;

  display: flex;
  justify-content: center;
  /* padding-top: 22rem; */
  text-shadow: 2px 2px rgba(0, 0, 0, 0.582);
}
h2 {
    font-weight: 3rem;
  font-family: "Montserrat", sans-serif;
   display: flex;
  justify-content: center;
  color: white;
  text-shadow: 0px 0px 8px rgba(255 255 255 / 0.58);
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
/* h2 {
  color: black;
  font-family: "Noto Sans Mono", monospace;
} */
/* h3 {
  margin: 40px 0 0;
} */
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
s
