<template>
  <section id="contact" class="text-light" data-aos="fade-up">
    <div class="container">
      <h1>Contact Me</h1>
      <div class="row">
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
      </div>
      <div class="row">
        <div class="col-6 p-3">
          <div class="row">
            <div class="form-container">
              <form action="https://formspree.io/f/moqrgdro" method="POST">
                <div class="col">
                  <input
                    type="text"
                    class="form-control mb-2 bg-dark text-light"
                    placeholder="name"
                    aria-label="name"
                    name="name"
                  />
                </div>
                <div class="col">
                  <input
                    type="email"
                    class="form-control mb-2 bg-dark text-light"
                    placeholder="email"
                    aria-label="email"
                    name="email"
                    required
                  />
                </div>
                <select
                  class="form-select mb-2 bg-dark text-light"
                  aria-label="subject"
                  name="subject"
                  placeholder="subject"
                >
                  <option selected>subject</option>
                  <option value="1">query</option>
                  <option value="2">work opportunity</option>
                  <option value="3">personal</option>
                </select>
                <div class="mb-3">
                  <textarea
                    class="form-control bg-dark text-light"
                    id="exampleFormControlTextarea1"
                    rows="3"
                    name="message"
                    placeholder="message"
                  ></textarea>
                </div>
                <button type="submit" class="btn btn-outline-light">
                  Submit
                </button>
              </form>
            </div>
          </div>
        </div>
        <div class="col-6">
          <div class="map-container m-2">
            <iframe
              class="p-2"
              src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d13233.069675818386!2d18.4926986!3d-33.9856643!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x9c746d268c8e0ad9!2sLife%20Choices!5e0!3m2!1sen!2sza!4v1658310399082!5m2!1sen!2sza"
              width="450"
              height="300"
              style="border: 0"
              allowfullscreen=""
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
            ></iframe>
          </div>
          <h1 class="address">
            Location: 314 Imam Haron Rd, Lansdowne, Cape Town, 7780
          </h1>
        </div>
      </div>
      <div class="row"></div>
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
#contact {
  background: linear-gradient(rgba(0, 0, 0, 0.288), rgba(0, 0, 0, 0.288)),
    url("https://i.postimg.cc/V6s7NH87/brent-ninaber-zr-Ojc-QXAdvk-unsplash.jpg");
  background-size: cover;
  background-position: center;
  min-height: 100vh;
  color: white;
  display: flex;
  flex-direction: column;
  justify-content: center;
  z-index: 1;
}
form {
  width: 100%;
  padding-left: 4rem;
}
.map-container {
  width: 90%;
  margin-top: 2rem;
  height: 25rem;
}
iframe {
  width: 90%;
  height: 75%;
}
li {
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 1.1rem;
}
a {
  color: #545657;
  text-decoration: none;
}
a:hover {
  color: #33657e;
  text-decoration: none;
}
.container {
  z-index: 2;
}
.container[data-v-df212a54] {
  z-index: 2;
  padding-bottom: 193px;
}
@media screen and (max-width: 935px) {
  .col-6 {
    flex: 0 0 auto;
    display: flex;
    flex-direction: column;
  }
  .row > *[data-v-df212a54] {
    flex-shrink: 0;
    width: 100%;
    max-width: 100%;
    padding-right: calc(var(--bs-gutter-x) * 0.5);
    padding-left: calc(var(--bs-gutter-x) * 0.5);
    margin-top: var(--bs-gutter-y);
    display: flex;
    flex-direction: column;
    padding-bottom: 26px px;
  }
}
.form-control {
  display: block;
  width: 75%;
  padding: 0.375rem 0.75rem;
  font-size: 1rem;
  font-weight: 500;
  line-height: 1.5;
  color: #212529;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ced4da;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
  font-family: "Varela Round", sans-serif;
}
button {
  display: flex;
  justify-content: center;
  width: 74%;
}
.form-select {
  display: block;
  width: 75%;
  padding: 0.375rem 0.75rem;
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.5;
  color: #212529;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ced4da;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
  font-family: "Varela Round", sans-serif;
}
.address {
  display: none;
}
h1 {
  padding-top: 70px;
  font-family: "Varela Round", sans-serif;
  align-content: center;
  justify-content: center;
  align-items: center;
  display: grid;
  padding-bottom: 20px;
  font-size: 7rem;
}
h1:after {
  content: "";
  width: 100%;
  color: black;
}
iframe {
  filter: invert();
}
@media screen and (max-width: 467px) {
  .map-container {
    width: 100%;
    margin-top: 2rem;
    height: 20rem;
  }
  h1 {
    padding-top: 70px;
    font-family: "Varela Round", sans-serif;
    align-content: center;
    justify-content: center;
    align-items: center;
    display: grid;
    padding-bottom: 20px;
    font-size: 3rem;
  }
}
</style>
