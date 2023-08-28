<!-- eslint-disable -->
<template>
  <div class="projects" id="myworks-section">
    <h1>my work</h1>
    <!-- Grid View -->
    <div class="row h-100 gy-0 gy-md-2">
      <!-- project -->
      <div class="col-6 col-sm-4 p-0 p-sm-2 mb-4 text-center">
        <!-- item -->
        <div class="d-inline-block portfolio-item">
          <!-- project logo -->
          <div class="portfolio-item-image-wrapper">
            <img class="logo" src="../assets/project-logo-11.png" alt="logo" />
          </div>
          <!-- project info -->
          <div class="portfolio-item-description">
            <a
              href="https://todo-app-vue-rho.vercel.app/"
              target="_blank"
              class="btn btn-link portfolio-item-title mt-1 mb-0 pb-0"
            >
              todo -app
            </a>
            <p class="portfolio-item-category text-muted">Management</p>
          </div>
        </div>
      </div>
      <!-- project -->
      <div class="col-6 col-sm-4 p-0 p-sm-2 mb-4 text-center">
        <!-- item -->
        <div class="d-inline-block portfolio-item">
          <!-- project logo -->
          <div class="portfolio-item-image-wrapper">
            <img class="logo" src="../assets/project-logo-12.png" alt="logo" />
          </div>
          <!-- project info -->
          <div class="portfolio-item-description">
            <a
              href="https://e-commerce-website-chi-snowy.vercel.app/"
              target="_blank"
              class="btn btn-link portfolio-item-title mt-1 mb-0 pb-0"
            >
              E-commerce
            </a>
            <p class="portfolio-item-category text-muted">Business</p>
          </div>
        </div>
      </div>
      <!-- project -->
      <div class="col-6 col-sm-4 p-0 p-sm-2 mb-4 text-center">
        <!-- item -->
        <div class="d-inline-block portfolio-item">
          <!-- project logo -->
          <div class="portfolio-item-image-wrapper">
            <img class="logo" src="../assets/project-logo-13.png" alt="logo" />
          </div>
          <!-- project info -->
          <div class="portfolio-item-description">
            <a
              href="https://weather-app-livid-phi.vercel.app/"
              target="_blank"
              class="btn btn-link portfolio-item-title mt-1 mb-0 pb-0"
            >
              Weathe-App
            </a>
            <p class="portfolio-item-category text-muted">Geography</p>
          </div>
        </div>
      </div>
      <!-- project -->
      <div class="col-6 col-sm-4 p-0 p-sm-2 mb-4 text-center">
        <!-- item -->
        <div class="d-inline-block portfolio-item">
          <!-- project logo -->
          <div class="portfolio-item-image-wrapper">
            <img class="logo" src="../assets/project-logo-14.png" alt="logo" />
          </div>
          <!-- project info -->
          <div class="portfolio-item-description">
            <a
              href="https://memory-game-pxuxy3r0a-fathi-fayez.vercel.app/"
              target="_blank"
              class="btn btn-link portfolio-item-title mt-1 mb-0 pb-0"
            >
              Memory-Game
            </a>
            <p class="portfolio-item-category text-muted">Games</p>
          </div>
        </div>
      </div>
      <!-- project -->
      <div class="col-6 col-sm-4 p-0 p-sm-2 mb-4 text-center">
        <!-- item -->
        <div class="d-inline-block portfolio-item">
          <!-- project logo -->
          <div class="portfolio-item-image-wrapper">
            <img class="logo" src="../assets/project-logo-15.png" alt="logo" />
          </div>
          <!-- project info -->
          <div class="portfolio-item-description">
            <a
              href="https://travel-app-blond.vercel.app/"
              target="_blank"
              class="btn btn-link portfolio-item-title mt-1 mb-0 pb-0"
            >
              Travel-App
            </a>
            <p class="portfolio-item-category text-muted">Traveling</p>
          </div>
        </div>
      </div>
      <!-- project -->
      <div class="col-6 col-sm-4 p-0 p-sm-2 mb-4 text-center">
        <!-- item -->
        <div class="d-inline-block portfolio-item">
          <!-- project logo -->
          <div class="portfolio-item-image-wrapper">
            <img class="logo" src="../assets/project-logo-16.png" alt="logo" />
          </div>
          <!-- project info -->
          <div class="portfolio-item-description">
            <a
              href="https://search-meals-website.vercel.app/"
              target="_blank"
              class="btn btn-link portfolio-item-title mt-1 mb-0 pb-0"
            >
              Mealantik
            </a>
            <p class="portfolio-item-category text-muted">Food & Drink</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<!-- eslint-disable -->
<script>
export default {
  name: "myWorks",
};
</script>
<!-- eslint-disable -->
<style scoped lang="scss">
.projects {
  padding: 100px 0;
}
.portfolio-item-image-wrapper {
  cursor: pointer;
  margin: 0 auto;
  position: relative;
  padding: 0;
  overflow: hidden;

  border-radius: 30px;
  height: min(30vw, 100px);
  width: min(30vw, 100px);

  .logo {
    width: 100%;
    height: 100%;
  }
}
</style>
