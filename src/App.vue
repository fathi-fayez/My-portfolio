<template>
  <navigation-bullets></navigation-bullets>
  <!-- nav bar -->
  <navBar />
  <!-- header -->
  <Header></Header>
  <!-- about section -->
  <about-section></about-section>
  <!-- my skills section -->
  <my-skills></my-skills>
  <!-- my works section -->
  <myWorks></myWorks>
  <!-- footer -->
  <Footer></Footer>
  <router-view />
</template>

<script>
import navigationBullets from "@/components/navigation-bullets";
import navBar from "@/components/navComponent.vue";
import Header from "@/components/Header.vue";
import AboutSection from "./components/aboutSection.vue";
import MySkills from "./components/mySkills.vue";
import myWorks from "./components/myNewWorks.vue";
import Footer from "./components/Footer.vue";
export default {
  name: "HomeView",
  components: {
    navigationBullets,
    navBar,
    Header,
    AboutSection,
    MySkills,
    myWorks,
    Footer,
  },
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,700&family=Montserrat:wght@700&family=Roboto+Slab:wght@200;500;700&family=Roboto:wght@100;300;400&display=swap");
#app {
  font-family: "Fraunces", serif;
  font-family: "Montserrat", sans-serif;
  font-family: "Roboto", sans-serif;
  font-family: "Roboto Slab", serif;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
h1 {
  padding-bottom: 50px;
  text-transform: uppercase;
  text-align: center;
  position: relative;
}
h1::after {
  content: "";
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
  bottom: 20px;
  width: 300px;
  height: 3px;
  background-color: black;
}
</style>
