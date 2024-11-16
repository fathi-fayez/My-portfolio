<!-- eslint-disable -->
<template>
  <div class="about" id="about-section">
    <div class="container">
      <h1>about me</h1>
      <p>
        I’m a Junior Front-End Developer located in Egypt. I have a serious
        passion for UI effects, animations, and creating intuitive, dynamic user
        experiences.
      </p>
      <p>
        I'm a well organized person, problem solver, independent employee with
        high attention to detail,
      </p>
      <p>
        And I'm interested in the entire creative frontend spectrum and working
        on ambitious projects with positive people.
      </p>
      <a
        class="btn btn-primary btn-xl mt-4"
        href="https://drive.google.com/uc?export=download&id=1djCgwK80LPkHm86R1vvS_f-WMRO9U6W1
"

        download="Your-Resume.pdf"
        >Download Resume</a
      >
    </div>
  </div>
</template>
<!-- eslint-disable -->
<script>
export default {
  name: "aboutSection",
};
</script>
<!-- eslint-disable -->
<style scoped lang="scss">
.about {
  background: white;
  padding: 100px 0;
  text-align: center;
  .container {
    width: 60%;
    p {
      padding: 20px 0;
    }
    a {
      padding: 20px 50px;
    }
  }
}
</style>
