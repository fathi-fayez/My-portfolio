<!-- eslint-disable -->
<template>
  <div class="mySkills" id="myskills-section">
    <div class="container">
      <h1>My Skills</h1>
      <div class="row text-center gy-2 gy-lg-5 pt-lg-2">
        <!-- skill -->
        <div class="col-6 col-sm-4 col-lg-3">
          <span><i class="fa-brands fa-html5" style="color: #e34f26"></i></span>
          <h4 class="text-uppercase">html</h4>
        </div>
        <!-- skill -->
        <div class="col-6 col-sm-4 col-lg-3">
          <span
            ><i class="fa-brands fa-css3-alt" style="color: #002561"></i
          ></span>
          <h4 class="text-uppercase">css</h4>
        </div>
        <!-- skill -->
        <div class="col-6 col-sm-4 col-lg-3">
          <span><i class="fa-brands fa-js" style="color: #f7df1e"></i></span>
          <h4 class="text-uppercase">js</h4>
        </div>
        <!-- skill -->
        <div class="col-6 col-sm-4 col-lg-3">
          <span><i class="fa-brands fa-sass" style="color: #c69"></i></span>
          <h4 class="text-uppercase">sass</h4>
        </div>
        <!-- skill -->
        <div class="col-6 col-sm-4 col-lg-3">
          <span><i class="fa-brands fa-vuejs" style="color: #42b883"></i></span>
          <h4 class="text-uppercase">vue js</h4>
        </div>
        <!-- skill -->
        <div class="col-6 col-sm-4 col-lg-3">
          <span
            ><i class="fa-brands fa-bootstrap" style="color: #4c0bce"></i
          ></span>
          <h4 class="text-uppercase">bootstrap</h4>
        </div>
        <!-- skill -->
        <div class="col-6 col-sm-4 col-lg-3">
          <span><i class="fa-brands fa-github"></i></span>
          <h4 class="text-uppercase">git & github</h4>
        </div>
        <!-- skill -->
        <div class="col-6 col-sm-4 col-lg-3">
          <img
            class="tailwind-image"
            src="../assets/images/skills-logo/download-removebg-preview.png"
            alt=""
          />
          <h4 class="text-uppercase">tailwind</h4>
        </div>
        <!-- skill -->
        <div class="col-6 col-sm-4 col-lg-3">
          <img
            src="../assets/images/skills-logo/vuetify_logo_icon_249240.png"
            alt=""
          />
          <h4 class="text-uppercase">vuetify</h4>
        </div>
        <!-- skill -->
        <div class="col-6 col-sm-4 col-lg-3">
          <img
            class="typescript-image"
            src="../assets/images/skills-logo/download.png"
            alt=""
          />
          <h4 class="text-uppercase">typescript</h4>
        </div>
        <!-- skill -->
        <div class="col-6 col-sm-4 col-lg-3">
          <img
            src="../assets/images/skills-logo/pugjs_logo_icon_170825.png"
            alt=""
          />
          <h4 class="text-uppercase">pug js</h4>
        </div>
        <!-- skill -->
        <div class="col-6 col-sm-4 col-lg-3">
          <span><i class="fa-brands fa-gulp" style="color: #b80000"></i></span>
          <h4 class="text-uppercase">gulp js</h4>
        </div>
        <!-- skill -->
        <div class="col-6 col-sm-4 col-lg-3">
          <img
            src="../assets/images/skills-logo/file_type_jest_icon_130514.png"
            alt=""
          />
          <h4 class="text-uppercase">jest js</h4>
        </div>
        <!-- skill -->
        <div class="col-6 col-sm-4 col-lg-3">
          <img
            src="../assets/images/skills-logo/nuxt_js_logo_icon_145021.png"
            alt=""
          />
          <h4 class="text-uppercase">nuxt js</h4>
        </div>
      </div>
    </div>
  </div>
</template>
<!-- eslint-disable -->
<script>
export default {
  name: "mySkills",
};
</script>
<!-- eslint-disable -->
<style scoped lang="scss">
.mySkills {
  background: #ffe4d6;
  padding: 100px 0;
  text-align: center;

  svg {
    font-size: 50px;
    margin-bottom: 10px;
    border-radius: 50%;
    padding: 30px;
  }
  img {
    width: 100px;
  }
  .tailwind-image {
    margin-bottom: 20px;
    padding: 30px;
    width: 130px;
  }
  .typescript-image {
    padding: 30px;
    width: 130px;
  }
}
</style>
