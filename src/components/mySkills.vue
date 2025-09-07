<!-- eslint-disable -->
<template>
  <div class="mySkills" id="myskills-section">
    <div class="container">
      <h1>My Skills</h1>
      <div class="skill-categories">
        <!-- Core Web Technologies -->
        <div class="skill-category">
          <h3>Core Web Technologies</h3>
          <div class="row text-center gy-3">
            <div class="col-6 col-sm-4 col-lg-3 skill-item">
              <span><i class="fa-brands fa-html5" style="color: #e34f26"></i></span>
              <h4 class="text-uppercase">HTML</h4>
            </div>
            <div class="col-6 col-sm-4 col-lg-3 skill-item">
              <span><i class="fa-brands fa-css3-alt" style="color: #002561"></i></span>
              <h4 class="text-uppercase">CSS</h4>
            </div>
            <div class="col-6 col-sm-4 col-lg-3 skill-item">
              <span><i class="fa-brands fa-js" style="color: #f7df1e"></i></span>
              <h4 class="text-uppercase">JavaScript</h4>
            </div>
            <div class="col-6 col-sm-4 col-lg-3 skill-item">
              <img src="../assets/images/skills-logo/download.png" alt="TypeScript" />
              <h4 class="text-uppercase">TypeScript</h4>
            </div>
          </div>
        </div>

        <!-- Frameworks & Libraries -->
        <div class="skill-category">
          <h3>Frameworks & Libraries</h3>
          <div class="row text-center gy-3">
            <div class="col-6 col-sm-4 col-lg-3 skill-item">
              <img src="../assets/images/skills-logo/images.png" alt="Nuxt.js" />
              <h4 class="text-uppercase">React</h4>
            </div>

            <div class="col-6 col-sm-4 col-lg-3 skill-item">
              <img src="../assets/images/skills-logo/next2.jpg" alt="Nuxt.js" />
              <h4 class="text-uppercase">Next.js</h4>
            </div>

            <div class="col-6 col-sm-4 col-lg-3 skill-item">
              <span><i class="fa-brands fa-vuejs" style="color: #42b883"></i></span>
              <h4 class="text-uppercase">Vue.js</h4>
            </div>

            <div class="col-6 col-sm-4 col-lg-3 skill-item">
              <img src="../assets/images/skills-logo/nuxt_js_logo_icon_145021.png" alt="Nuxt.js" />
              <h4 class="text-uppercase">Nuxt.js</h4>
            </div>
          </div>
        </div>

        <!-- Styling & Preprocessors -->
        <div class="skill-category">
          <h3>Styling & Preprocessors</h3>
          <div class="row text-center gy-3">
            <div class="col-6 col-sm-4 col-lg-3 skill-item">
              <span><i class="fa-brands fa-sass" style="color: #c69"></i></span>
              <h4 class="text-uppercase">SASS</h4>
            </div>
            <div class="col-6 col-sm-4 col-lg-3 skill-item">
              <span><i class="fa-brands fa-bootstrap" style="color: #4c0bce"></i></span>
              <h4 class="text-uppercase">Bootstrap</h4>
            </div>
            <div class="col-6 col-sm-4 col-lg-3 skill-item">
              <img src="../assets/images/skills-logo/download-removebg-preview.png" alt="Tailwind" />
              <h4 class="text-uppercase">Tailwind</h4>
            </div>
            <div class="col-6 col-sm-4 col-lg-3 skill-item">
              <img src="../assets/images/skills-logo/vuetify_logo_icon_249240.png" alt="Vuetify" />
              <h4 class="text-uppercase">Vuetify</h4>
            </div>
          </div>
        </div>

        <!-- Tools & Version Control -->
        <div class="skill-category">
          <h3>Tools & Version Control</h3>
          <div class="row text-center gy-3">
            <div class="col-6 col-sm-4 col-lg-3 skill-item">
              <span><i class="fa-brands fa-github"></i></span>
              <h4 class="text-uppercase">Git & GitHub</h4>
            </div>
            <div class="col-6 col-sm-4 col-lg-3 skill-item">
              <img src="../assets/images/skills-logo/pugjs_logo_icon_170825.png" alt="Pug.js" />
              <h4 class="text-uppercase">Pug.js</h4>
            </div>
            <div class="col-6 col-sm-4 col-lg-3 skill-item">
              <span><i class="fa-brands fa-gulp" style="color: #b80000"></i></span>
              <h4 class="text-uppercase">Gulp.js</h4>
            </div>
            <div class="col-6 col-sm-4 col-lg-3 skill-item">
              <img src="../assets/images/skills-logo/file_type_jest_icon_130514.png" alt="Jest" />
              <h4 class="text-uppercase">Jest</h4>
            </div>

          </div>
        </div>

      </div>
    </div>
  </div>
</template>
<!-- eslint-disable -->
<script>
export default {
  name: "MySkills",
};
</script>
<!-- eslint-disable -->
<style scoped lang="scss">
.mySkills {
  background: #ffe4d6;
  padding: 80px 0;
  text-align: center;

  h1 {
    font-size: 2.5rem;
    margin-bottom: 40px;
    color: #333;
  }

  .skill-categories {
    display: flex;
    flex-direction: column;
    gap: 40px;
  }

  .skill-category {
    background: #fff;
    border-radius: 10px;
    padding: 20px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);

    h3 {
      font-size: 1.5rem;
      margin-bottom: 20px;
      color: #444;
    }

    .row {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      align-items: stretch;
    }

    .skill-item {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: space-between;
      min-height: 150px;
      /* Ensure all items have the same height */
      padding: 15px;
    }

    span {
      display: flex;
      justify-content: center;
      align-items: center;
      width: 80px;
      height: 80px;
    }

    img {
      height: 80px;
    }

    img,
    svg {
      width: 80px;
      font-size: 50px;
      border-radius: 50%;
      padding: 15px;
      background: #f5f5f5;
      object-fit: contain;
      /* Ensure images fit without distortion */
      transition: transform 0.3s ease;
    }

    h4 {
      font-size: 1rem;
      margin-top: 10px;
      color: #555;
      flex-grow: 1;
      /* Ensure text aligns consistently */
      display: flex;
      align-items: center;
    }

    .skill-item:hover {

      svg,
      img {
        transform: scale(1.1);
      }
    }
  }
}
</style>