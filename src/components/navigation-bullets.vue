<!-- eslint-disable -->
<template>
  <div class="nav-bullets">
    <div class="bullet" v-scroll-to="'#about-section'">
      <div class="tool-tip">About Me</div>
    </div>

    <div class="bullet" v-scroll-to="'#myskills-section'">
      <div class="tool-tip">My Skills</div>
    </div>
    <div class="bullet" v-scroll-to="'#myworks-section'">
      <div class="tool-tip">My Work</div>
    </div>
  </div>
</template>
<!-- eslint-disable -->
<script setup></script>
<!-- eslint-disable -->
<style scoped>
.nav-bullets {
  position: fixed;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
  width: 40px;
  z-index: 1000;
}
.bullet {
  width: 20px;
  height: 20px;
  /* background-color: red; */
  border: 3px solid #0d6efd;
  border-radius: 50%;
  margin: 10px auto;
  cursor: pointer;
  position: relative;
}
.bullet:hover .tool-tip {
  display: block;
}
.tool-tip {
  position: absolute;
  right: 10px;
  top: -7px;
  width: 100px;
  color: rgb(86, 84, 84);
  cursor: default;
  display: none;
  pointer-events: none;
}
</style>
