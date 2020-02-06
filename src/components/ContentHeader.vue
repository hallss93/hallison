<template>
  <div id="header" class="header">
    <div class="container text-center">
      <a class="sidebar-toggle pull-left btn btn-lg btn-none visible-xs"
        ><span aria-hidden="true" class="icon-menu"></span
      ></a>
      <ul class="list-inline hidden-xs list-nav">
        <li>
          <a
            href="#about"
            data-toggle="tooltip"
            title="Who's this dude?"
            class="smooth"
            >About</a
          >
        </li>
        <li>
          <a
            href="#skills"
            data-toggle="tooltip"
            title="Any cool tricks?"
            class="smooth"
            >Skills</a
          >
        </li>
        <!-- <li>
          <a
            href="#work"
            data-toggle="tooltip"
            title="Proof's in the pudding"
            class="smooth"
            >Work</a
          >
        </li> -->
        <!-- <li>
          <a
            href="#"
            class="contact-toggle"
            data-toggle="tooltip"
            title="Let's chat"
            >Contact</a
          >
        </li> -->
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContentHeader"
};
</script>
