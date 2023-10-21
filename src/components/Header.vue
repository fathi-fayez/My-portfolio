<!-- eslint-disable -->
<template>
  <header class="page-header d-flex">
    <!-- Background -->
    <div class="content-top-bg">
      <img src="../assets/header-bg.jpeg" alt="background-image" />
      <div class="content-top-bg-overlay"></div>
    </div>

    <!-- Bootstrap Container -->
    <div class="container m-auto pb-5">
      <div class="content-wrapper">
        <!-- Logo -->
        <img
          src="../assets/personal-logo-2.png"
          alt="logo"
          class="img-fluid logo rounded-circle"
        />

        <!-- Texts -->
        <h1 class="heading">Welcome, I'm Fathi Fayez</h1>
        <p class="subheading">frontEnd developer</p>

        <!-- Social Icons -->
        <div class="social-icons">
          <a
            href="https://github.com/fathi-fayez?tab=repositorieshttps://github.com/fathi-fayez?tab=repositories"
            target="_blank"
            ><i class="fa-brands fa-github" style="color: #4078c0"></i
          ></a>
          <a
            href="https://www.linkedin.com/in/fathi-fayez-0416671a6/"
            target="_blank"
            ><i class="fa-brands fa-linkedin" style="color: #0a66c2"></i
          ></a>
          <a
            href="https://www.facebook.com/profile.php?id=100005083479476"
            target="_blank"
            ><i class="fa-brands fa-facebook" style="color: #1877f2"></i
          ></a>
          <a href="mailto:fathifayez155@gmail.com" target="_blank"
            ><i class="fa-brands fa-google" style="color: #ea4335"></i
          ></a>
        </div>
      </div>
    </div>
  </header>
</template>
<!-- eslint-disable -->
<script>
export default {
  name: "Header",
};
</script>
<!-- eslint-disable -->
<style scoped lang="scss">
.content-top-bg {
  // background-image: url("../assets/header-bg.jpeg");
  background-position: center;
  background-size: cover;
  height: 100%;
  position: absolute;
  width: 100%;
  z-index: -1;

  img {
    position: absolute;
    animation: up-and-down 5s linear infinite;
    max-width: 100%;
  }
  .content-top-bg-overlay {
    position: relative;
    height: 100%;
    width: 100%;
    background-image: -webkit-gradient(
      linear,
      left top,
      left bottom,
      from(rgba(30, 30, 30, 0.73)),
      color-stop(70%, rgba(30, 30, 30, 0.86)),
      color-stop(80%, rgba(30, 30, 30, 0.99)),
      to(rgba(30, 30, 30, 1))
    );
    background-image: linear-gradient(
      180deg,
      rgba(30, 30, 30, 0.73) 0%,
      rgba(30, 30, 30, 0.86) 30%,
      rgba(30, 30, 30, 0.99) 60%,
      rgba(30, 30, 30, 1) 100%
    );
  }
}
.container {
  padding-left: 1rem;
  padding-right: 1rem;
}

.content-wrapper {
  padding-top: 100px;
  text-align: center;
  color: white;
}
.logo {
  min-height: 300px;
  max-height: 30vh;
}
.heading {
  font-size: 1.5rem;
  padding-bottom: 20px;
  margin: 2rem auto 0.75rem;
  text-transform: uppercase;
  overflow: hidden;
  white-space: nowrap;
  width: 331px;
  animation: control-width 1s steps(24) 2s both;
}
.heading::after {
  display: none;
}

.subheading {
  font-size: 1rem;
  color: white;
  animation: popup 3s 3.5s both;
}
.social-icons {
  font-size: 34px;
  a {
    margin: 10px;
  }
}
@keyframes up-and-down {
  0%,
  100% {
    top: 0;
  }

  50% {
    top: -30px;
  }
}
@keyframes control-width {
  from {
    width: 0;
  }
  to {
    width: 331px;
  }
}
@keyframes popup {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
</style>
