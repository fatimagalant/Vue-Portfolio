<template>
  <section id="testimonials" class="bg-dark text-light">
    <h1>Testimonials</h1>
    <h5 style="padding-bottom: 10px">Here's what a few people had to say:</h5>
    <div v-for="testimonial in testimonials" :key="testimonial.id">
      <div class="row">
        <!-- <div class="col"> -->
        <div class="card bg-dark">
          <img
            id="img"
            v-bind:src="testimonial.imgURL"
            class="rounded-circle mb-5"
          />
          <h2>{{ testimonial.name }}</h2>
          <p class="text-muted">{{ testimonial.occupation }}</p>
          <p>
            <i class="fa-solid fa-quote-left"></i>{{ testimonial.quote
            }}<i class="fa-solid fa-quote-right"></i>
          </p>
          <!-- </div> -->
        </div>
      </div>
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
  data() {
    return {
      testimonials: [
        {
          id: 1,
          imgURL: "https://i.postimg.cc/sg2XT9qq/Zoe-1.jpg",
          name: "Zoe Van Der Schyff",
          occupation: "Colleague",
          quote:
            "Fatima Galant is hard working and is a fast learner . She is very determined to finish what she started , and she'll work hard until she achieves it.",
        },
        {
          id: 2,
          imgURL: "https://i.postimg.cc/05JY9mkL/Ricardo-3.jpg",
          name: "Ricardo Ronan Moses",
          occupation: "Colleague",
          quote:
            "Fatima Galant is a very expressive  and hardworking young lady.  I cannot express enough how much commitment and consistency she is. Working alongside her has been an absolute pleasure and I would personally recommend her.",
        },
        {
          id: 3,
          imgURL: "https://i.postimg.cc/63VBhYVk/Natheerah-3.jpg",
          name: "Natheerah Abrahams",
          occupation: "Colleague",
          quote:
            "Fatima Galant is very dedicated and striving. She is also independent and would always figure out on her own how to do things.",
        },
        {
          id: 4,
          imgURL: "https://i.postimg.cc/s27zVwLM/Uzair-3.jpg",
          name: "Uzair Damonse",
          occupation: "Colleague",
          quote:
            "Fatima is one of most resilient and hard-working people I know. She is a great person to have as a teammate because she always assists in making the team better and giving ideas that impact projects immensely",
        },
        {
          id: 5,
          imgURL: "https://i.postimg.cc/hP6NfVTT/jason-v3.jpg",
          name: "Jason Wandrag",
          occupation: "Lecturer",
          quote:
            "Fatima is a very respectful and humble person. She shows great care for those around her and she strives to achieve the absolute best. She is an exceptionally well rounded person that will provide great value to any workplace she enters.",
        },
        {
          id: 6,
          imgURL: "https://i.postimg.cc/yNDFkXZh/Carla-1-1.jpg",
          name: "Carla Amy Lawrence",
          occupation: "Colleague",
          quote:
            "Fatima is an exceptional web developer. She is laser focused, highly skilled and determined to take on any task given to her. Her work ethic is highly commendable . It is a pleasure to have worked alongside her and I can, without a doubt, say that Fatima would be an asset and perfect addition to any team.",
        },
      ],
    };
  },
};
</script>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@1,300&family=Noto+Sans+Mono:wght@200;300&family=Noto+Serif+Display:wght@700&family=Poppins:wght@200&display=swap");
#testimonials {
  padding-top: 3rem;
}
#img {
  width: 250px;
  height: 250px;
  aspect-ratio: 1;
  object-fit: cover;
}
.card {
  background: linear-gradient(rgba(0, 0, 0, 0.242), rgba(0, 0, 0, 0.242)),
    url("https://i.postimg.cc/N0b07cQZ/mihaly-koles-5-V-W4z-Tq-Z74-unsplash.jpg");
  background-size: cover;
  background-attachment: fixed;
  background-position: center;
  border-radius: 0 !important;
  display: flex;
  justify-content: center;
  align-content: center;
  align-items: center;
  text-align-last: center;
  width: 1000px;
  padding: 20px;
}
.row {
  display: flex;
  justify-content: center;
  padding-bottom: 50px;
}

@media screen and (max-width: 400px) {
  .row {
    display: flex;
    justify-content: center;
  }
  .card {
    width: 500px;
  }
}
h1 {
  padding-top: 3rem;
 font-family: 'Varela Round', sans-serif;
  text-align: center;
  font-size: 6rem;
}
h2 {
 font-family: 'Varela Round', sans-serif;
}
h5 {
  font-family: 'Varela Round', sans-serif;
  text-align: center;
}
p {
 font-family: 'Varela Round', sans-serif;
}
</style>
