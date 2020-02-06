<template>
  <div class="content">
    <section id="main" class="mast mast-trans mast-head">
      <div class="container">
        <div data-spy="affix" data-offset-top="30" class="page-title">
          <h2 class="text-light">WEB DEVELOPER / DESKTOP DEVELOPER</h2>
          <h1 class="text-light bold">JS / DEVELOPER</h1>
          <hr class="separator" />
          <!-- <a href="#" class="contact-toggle btn btn-lg btn-border"
            ><span aria-hidden="true" class="icon-mail"></span> Contact Me</a
          > -->
          <ul class="list-inline list-social text-50 push-top-lg bk">
            <li>
              <a href="https://facebook.com/hallison.melo"
                ><img
                  src="~@/assets/img/icons8-facebook-200.png"
                  class="icon-new"
              /></a>
            </li>
            <li>
              <a href="https://www.instagram.com/hallison.pm"
                ><img
                  src="~@/assets/img/icons8-instagram-200.png"
                  class="icon-new"
              /></a>
            </li>
            <li>
              <a href="https://www.linkedin.com/in/hallss93"
               ><img
                  src="~@/assets/img/icons8-linkedin-200.png"
                  class="icon-new"
              /></a>
            </li>
            <li>
              <a href="https://github.com/hallss93"
               ><img
                  src="~@/assets/img/icons8-github-200.png"
                  class="icon-new"
              /></a>
            </li>
          </ul>
        </div>
      </div>
    </section>
    <content-header></content-header>

    <about></about>
    <skills></skills>
  </div>
</template>

<script>
import ContentHeader from "./ContentHeader";
import About from "./About";
import Skills from "./Skills";
export default {
  name: "ContentMain",
  components: { ContentHeader, About, Skills }
};
</script>
