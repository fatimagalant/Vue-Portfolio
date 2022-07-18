<template>
  <footer class="bg-black">
    <hr />
    <ul class="social-media-list">
      <li>
        <a
          href="https://www.linkedin.com/in/fatima-galant-778944228/"
          target="_blank"
          class="btn btn-light"
          style="border-radius: 50%"
          ><i class="fa-brands fa-linkedin"></i
        ></a>
      </li>
      <li>
        <a
          href="https://www.github.com/fatimagalant"
          target="_blank"
          class="btn btn-light"
          style="border-radius: 50%"
          ><i class="fa-brands fa-github"></i
        ></a>
      </li>
      <li>
        <a
          href="https://www.codepen.io/fatimagalant"
          target="_blank"
          class="btn btn-light"
          style="border-radius: 50%"
          ><i class="fa-brands fa-codepen"></i
        ></a>
      </li>
      <li>
        <a
          href="https://www.instagram.com/fatimagalant_"
          target="_blank"
          class="btn btn-light"
          style="border-radius: 50%"
          ><i class="fa-brands fa-instagram"></i></a
        ><br />
      </li>
    </ul>
    <hr />

    <div class="copyright">&copy; ALL RIGHTS RESERVED</div>
  </footer>
</template>
<script>
export default {};
</script>
<style>
/* .social-media-list {
  position: relative;
  font-size: 22px;
  text-align: center;
  width: 100%;
  margin: 0 auto;
  padding: 0;
}

.social-media-list li a {
  color: #fff;
}

.social-media-list li {
    } */

a {
  padding-bottom: 20px;
  position: relative;
  font-size: 22px;
  position: relative;
  display: inline-block;
  height: 60px;
  width: 60px;
  margin: 10px 3px;
  line-height: 60px;
  border-radius: 50%;
  color: #fff;
  background-color: rgb(27, 27, 27);
  cursor: pointer;
  transition: all 0.2s ease-in-out;
  text-align: center;
  width: 100%;
  margin: 0 auto;
  padding: 0;
}
#contact .btn {
  padding-top: 20px;
}
.btn:hover {
  color: #f0f0f0;
  background-color: #000;
}
#contactbtn:hover {
  background-color: #ffffff;
  color: #000;
}
.social-media-list li:after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 60px;
  height: 60px;
  line-height: 60px;
  border-radius: 50%;
  opacity: 0;
  box-shadow: 0 0 0 1px #fff;
  transition: all 0.2s ease-in-out;
}

/* .social-media-list li:hover {
  background-color: rgb(196, 196, 196);
} */

/* .social-media-list li:hover:after {
  opacity: 1;
  transform: scale(1.12);
  transition-timing-function: cubic-bezier(0.37, 0.74, 0.15, 1.65);
} */

/* .social-media-list li:hover a {
  color: #000;
} */

.copyright {
  font: 200 14px "Oswald", sans-serif;
  color: rgb(56, 56, 56);
  letter-spacing: 1px;
  text-align: center;
}

hr {
  border-color: rgba(255, 255, 255, 0.6);
}
</style>
