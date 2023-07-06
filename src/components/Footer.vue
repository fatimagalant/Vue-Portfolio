<template>
  <div id="footer">
    <!-- Site footer -->
    <footer class="footer">
      <div class="container">
        <div class="row">
          <div class="col-sm-12 col-md-6">
            <h6>About</h6>
            <p class="text-justify">
              I am a prospective fullstack developer. My tech stack consists of
              HTML5, CSS3, Javascript ES6, VueJs, MYSQL and NodeJS. It has been
              a challenging journey picking up these skills but it's also helped me take that step to start my web development career.
            </p>
          </div>

          <div class="col-xs-6 col-md-3">
            <h6>Skills</h6>
            <ul class="footer-links">
              <li>
                <a href="/projects"> HTML</a>
              </li>
              <li>
                <a href="/projects">CSS</a>
              </li>
              <li>
                <a href="/projects">Bootstrap</a>
              </li>
              <li>
                <a href="/projects">JavaScript</a>
              </li>
              <li>
                <a href="/projects">VueJS</a>
              </li>
              <li>
                <a href="/projects">NodeJS</a>
              </li>
            </ul>
          </div>

          <div class="col-xs-6 col-md-3">
            <h6>Quick Links</h6>
            <ul class="footer-links">
              <li><a href="/about">About Me</a></li>
              <li><a href="/contact">Contact Me</a></li>
              <li><a href="tel:0662091181">Give me a call</a></li>
              <li><a href="mailto:fatimagalant03@gmail.com">Email Me</a></li>
            </ul>
          </div>
        </div>
        <hr />
      </div>
      <div class="container">
        <div class="row">
          <div class="col-md-8 col-sm-6 col-xs-12">
            <p class="copyright-text">
              Copyright &copy; 2022 All Rights Reserved by
              <a href="/about">Fatima Galant</a>.
            </p>
          </div>

          <div class="col-md-4 col-sm-6 col-xs-12">
            <ul class="social-icons">
              <li>
                <a
                  href="https://www.linkedin.com/in/fatima-g-778944228/"
                  target="_blank"
                  ><i class="fa-brands fa-linkedin"></i
                ></a>
              </li>
              <li>
                <a href="https://www.github.com/fatimagalant" target="_blank"
                  ><i class="fa-brands fa-github"></i
                ></a>
              </li>
              <li>
                <a href="https://www.codepen.io/fatimagalant" target="_blank"
                  ><i class="fa-brands fa-codepen"></i
                ></a>
              </li>
              <li>
                <a
                  href="https://www.instagram.com/fatimagalant_"
                  target="_blank"
                  ><i class="fa-brands fa-instagram"></i
                ></a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.footer {
  background-color: #26272b;
  padding: 45px 0 20px;
  font-size: 15px;
  line-height: 24px;
  color: #737373;
}
.footer hr {
  border-top-color: #bbb;
  opacity: 0.5;
}
.footer hr.small {
  margin: 20px 0;
}
.footer h6 {
  color: #fff;
  font-size: 16px;
  text-transform: uppercase;
  margin-top: 5px;
  letter-spacing: 2px;
}
.footer a {
  color: #737373;
}
.footer a:hover {
  color: #3366cc;
  text-decoration: none;
}
.footer-links {
  padding-left: 0;
  list-style: none;
}
.footer-links li {
  display: block;
}
.footer-links a {
  color: #737373;
}
.footer-links a:active,
.footer-links a:focus,
.footer-links a:hover {
  color: #3366cc;
  text-decoration: none;
}
.footer-links.inline li {
  display: inline-block;
}
.footer .social-icons {
  text-align: right;
}
.footer .social-icons a {
  width: 40px;
  height: 40px;
  line-height: 40px;
  margin-left: 6px;
  margin-right: 0;
  border-radius: 100%;
  background-color: #33353d;
}
.copyright-text {
  margin: 0;
}
@media (max-width: 991px) {
  .footer [class^="col-"] {
    margin-bottom: 30px;
  }
}
@media (max-width: 767px) {
  .footer {
    padding-bottom: 0;
  }
  .footer .copyright-text,
  .footer .social-icons {
    text-align: center;
  }
}
.social-icons {
  padding-left: 0;
  margin-bottom: 0;
  list-style: none;
}
.social-icons li {
  display: inline-block;
  margin-bottom: 4px;
}
.social-icons li.title {
  margin-right: 15px;
  text-transform: uppercase;
  color: #96a2b2;
  font-weight: 700;
  font-size: 13px;
}
.social-icons a {
  background-color: #eceeef;
  color: #818a91;
  font-size: 16px;
  display: inline-block;
  line-height: 44px;
  width: 44px;
  height: 44px;
  text-align: center;
  margin-right: 8px;
  border-radius: 100%;
  -webkit-transition: all 0.2s linear;
  -o-transition: all 0.2s linear;
  transition: all 0.2s linear;
}
.social-icons a:active,
.social-icons a:focus,
.social-icons a:hover {
  color: rgb(0, 0, 0);
  background-color: #fff;
}
.social-icons.size-sm a {
  line-height: 34px;
  height: 34px;
  width: 34px;
  font-size: 14px;
}
.social-icons a.linkedin:hover {
  background-color: #3b5998;
}
.social-icons a.codepen:hover {
  background-color: #00aced;
}
.social-icons a.github:hover {
  background-color: #007bb6;
}
.social-icons a.instagram:hover {
  background-color: #ea4c89;
}
@media (max-width: 767px) {
  .social-icons li.title {
    display: block;
    margin-right: 0;
    font-weight: 600;
  }
}
</style>
