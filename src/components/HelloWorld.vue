<template>
  <section id="Landing">
    <h1>
      I am Fatima Galant <br />
      Aspiring Web Developer
    </h1>
  </section>
  <section id="about"></section>
</template>

<script></script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
* {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  scroll-behavior: smooth;
}
#Landing {
  background: linear-gradient(rgba(0, 0, 0, 0.242), rgba(0, 0, 0, 0.242)),
    url(https://i.postimg.cc/BQwrtsNf/emile-perron-xr-VDYZRGdw4-unsplash.jpg);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  min-height: 100vh;
}
@media screen and (max-width: 896px) {
  #Landing {
    height: 50%;
  }
}
h1 {
  color: white;
  font-family: "Noto Serif Display", monospace;
  display: flex;
  justify-content: center;
  padding: 27rem;
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
