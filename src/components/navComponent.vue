<!-- eslint-disable -->
<template>
  <nav class="navbar navbar-expand-lg sticky-top" ref="navbar">
    <div class="container-fluid justify-content-around">
      <a class="navbar-brand text-light" href="#">My Portfolio</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <a @click="closeNavbar" v-scroll-to="'#about-section'" class="nav-link text-light" aria-current="page"
            href="#">About Me</a>
          <a @click="closeNavbar" v-scroll-to="'#myskills-section'" class="nav-link text-light" href="#">My Skills</a>
          <a @click="closeNavbar" v-scroll-to="'#myworks-section'" class="nav-link text-light" href="#">My Work</a>
        </div>
      </div>
    </div>
  </nav>
</template>
<!-- eslint-disable -->
<script>
export default {
  name: "navBar",
  methods: {
    closeNavbar() {
      const navbarCollapse = document.getElementById("navbarNavAltMarkup");
      if (navbarCollapse.classList.contains("show")) {
        navbarCollapse.classList.remove("show");
      }
    },

    handleClickOutside(event) {
      const navbar = this.$refs.navbar;
      const navbarCollapse = document.getElementById("navbarNavAltMarkup");
      if (
        navbarCollapse.classList.contains("show") &&
        navbar &&
        !navbar.contains(event.target)
      ) {
        navbarCollapse.classList.remove("show");
      }
    },
  },
  mounted() {
    document.addEventListener("click", this.handleClickOutside);
  },
  beforeUnmount() {
    document.removeEventListener("click", this.handleClickOutside);
  },
};
</script>
<!-- eslint-disable -->
<style lang="scss" scoped>
nav {
  // animation: nav ease-in-out both;
  // animation-timeline: scroll();
  // animation-range: 0 90vh;
  padding: 10px;
  background-color: black;
  overflow: visible;
  margin: 0 auto;
  transition: all 0.3s;
}

.collapse {
  flex-grow: 0;

  a {
    margin-left: 20px;
    transition: 0.3s;
  }
}

.nav-link:hover {
  background-color: rgb(55, 13, 239);
  border-radius: 5px;
  padding: 10px;
}


.navbar-toggler-icon {
  filter: brightness(0.3) invert(1) contrast(2);
}



// @keyframes nav {
//   0% {
//     width: 100%;
//   }
//   70% {
//     width: 100%;
//     border-radius: 0;
//     translate: 0 -100%;
//   }
//   90% {
//     top: 0;
//     width: min(600px, 100%);
//     translate: 0 -100%;
//     box-shadow: 0 0 0 rgba(0 0 0 / 0);
//   }
//   100% {
//     width: min(900px, 100%);
//     background-color: rgb(156, 156, 179);
//     top: 5px;
//     height: 48px;
//     border-radius: 99em;
//     translate: 0 0;
//     box-shadow: inset 0 1px 1px white, 0 0 1px rgba(0 0 0 / 0.9),
//       0 8px 14px rgba(0 0 0 / 0.3);
//   }
// }</style>
