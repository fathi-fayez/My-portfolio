<!-- eslint-disable -->
<template>
  <nav class="navbar navbar-expand-lg bg-black sticky-top">
    <div class="container-fluid justify-content-around">
      <a class="navbar-brand text-light" href="#">My Portfolio</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <a
            v-scroll-to="'#about-section'"
            class="nav-link active text-light"
            aria-current="page"
            href="#"
            >About Me</a
          >
          <a
            v-scroll-to="'#myskills-section'"
            class="nav-link text-light"
            href="#"
            >My Skills</a
          >
          <a
            v-scroll-to="'#myworks-section'"
            class="nav-link text-light"
            href="#"
            >My Work</a
          >
        </div>
      </div>
    </div>
  </nav>
</template>
<!-- eslint-disable -->
<script>
export default {
  name: "navBar",
};
</script>
<!-- eslint-disable -->
<style lang="scss" scoped>
.collapse {
  flex-grow: 0;

  a {
    margin-left: 20px;
    transition: 0.3s;
  }
}
.nav-link:hover {
  background-color: rgb(55, 13, 239);
}
</style>
