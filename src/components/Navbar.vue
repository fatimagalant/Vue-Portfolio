<template>
  <button id="menu-btn" type="button" @click="toggleNav()">
    <i class="fa-solid fa-bars"></i>
  </button>
  <nav class="nav-links">
    <router-link class="items" @click="toggleNav()" to="/">
      <i class="fa-solid fa-code"></i
    ></router-link>

    <router-link class="items" @click="toggleNav()" to="/">Home</router-link>
    <router-link class="items" @click="toggleNav()" to="/about"
      >About</router-link
    >
    <router-link class="items" @click="toggleNav()" to="/projects"
      >Projects</router-link
    >
    <router-link class="items" @click="toggleNav()" to="/testimonials"
      >Testimonials</router-link
    >
    <router-link class="items" @click="toggleNav()" to="/contact"
      >Contact</router-link
    >

    <button
      id="close-btn"
      class="text-light"
      type="button"
      @click="toggleNav()"
    >
      <i class="fa-solid fa-xmark"></i>
    </button>
  </nav>
</template>
<script>
export default {
  data() {
    return {};
  },
  methods: {
    toggleNav() {
      document.querySelector(".nav-links").classList.toggle("active");
    },
  },
};
</script>
<style scoped>
#close-btn {
  margin-left: 19rem;
  margin-top: 3rem;
  font-size: 2rem;
  position: absolute;
  border: none;
  background: transparent;
  color: whitesmoke;
  transform-origin: 0 0;
  transform: rotate(90deg);
}
#menu-btn {
  color: grey;
  z-index: 90;
  font-size: 2rem;
  position: fixed;
  top: 10px;
  right: 10px;
  border: none;
  background: transparent;
  transform-origin: 0 0;
  transform: rotate(90deg);
}
fa-solid {
  width: 8rem;
  height: auto;
  transition: all ease-in-out 0.5s;
}
#goat-img:hover {
  filter: invert();
}
.items {
  padding: 0.5rem;
  font-size: 3rem;
  list-style-type: none;
  --bs-text-opacity: 1;
  color: grey;
  transition: all ease-in-out 0.5s;
  text-decoration: none;
}
.items:hover {
  color: whitesmoke;
}

.nav-links {
  z-index: 100;
  font-family: fancy;
  position: fixed;
  top: -150%;
  /* left: 0; */
  right: 0;
  height: 105vh;
  background-color: black;
  display: flex;
  flex-flow: column nowrap;
  align-items: flex-start;
  transition: top 0.3s linear;
  font-family: "Noto Serif Display", monospace;
}
@media screen and (max-width: 928px) {
  .nav-links {
    z-index: 100;
    font-family: fancy;
    position: fixed;
    top: -150%;
    left: 0;
    right: 0;
    height: 105vh;
    background-color: black;
    display: flex;
    flex-flow: column nowrap;
    align-items: flex-start;
    transition: top 0.3s linear;
    font-family: "Noto Serif Display", monospace;
  }
  #close-btn {
    margin-left: 54rem;
    margin-top: 3rem;
    font-size: 2rem;
    position: absolute;
    border: none;
    background: transparent;
    color: whitesmoke;
    transform-origin: 0 0;
    transform: rotate(90deg);
  }
}
@media screen and (max-width: 800px) {
  .nav-links {
    z-index: 100;
    font-family: fancy;
    position: fixed;
    top: -150%;
    left: 0;
    right: 0;
    height: 105vh;
    background-color: black;
    display: flex;
    flex-flow: column nowrap;
    align-items: flex-start;
    transition: top 0.3s linear;
    font-family: "Noto Serif Display", monospace;
  }
  #close-btn {
    margin-left: 54rem;
    margin-top: 3rem;
    font-size: 2rem;
    position: absolute;
    border: none;
    background: transparent;
    color: whitesmoke;
    transform-origin: 0 0;
    transform: rotate(90deg);
  }
}
.nav-links.active {
  top: 0;
}
@media only screen and (max-width: 600px) {
  #close-btn {
    margin-left: 21rem;
    margin-top: 2rem;
    font-size: 1rem;
  }
  #menu-btn {
    position: fixed;
    right: -2rem;
    font-size: 1rem;
  }
  .items {
    font-size: 2rem;
  }
}
</style>
