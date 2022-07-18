<template>
  <section id="Landing">
    <h1>
      I am Fatima Galant <br />
      Aspiring Web Developer
    </h1>
  </section>
  <section id="about"></section>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
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
#Landing {
  background-image: url("https://i.postimg.cc/sXRgSxQg/giphy-gif-cid-790b7611ee22a7bf2e5fa8cf21e477c10fb419fed2f4082f-rid-giphy.gif");
  background-attachment: fixed;
  background-position: center;
  background-size: cover;
  min-height: 100vh;
  z-index: -1;
}
@media screen and (max-width: 896px) {
  #Landing {
    background-position: center;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
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
