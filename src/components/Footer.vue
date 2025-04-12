<!-- eslint-disable -->
<template>
  <footer class="page-footer">
    <div class="container">
      <div class="row">
        <!-- Footer Extra Links -->
        <div class="col-lg-4 page-footer-column">
          <h4 class="text-uppercase mb-4"> <i class="fa fa-phone me-2"></i>Phones</h4>
          <p>
            <i class="fa-solid fa-phone" style="color: #ffffff"></i> +2015 5039
            5381
          </p>
          <p>
            <i class="fa-solid fa-phone" style="color: #ffffff"></i> +2010 2271
            6283
          </p>

        </div>

        <!-- Footer Social Icons -->
        <div class="col-lg-4 page-footer-column">
          <h4 class="text-uppercase mb-4"> <i class="fa fa-link me-2"></i>Connect With Me</h4>
          <div class="social-icons">
            <a href="https://github.com/fathi-fayez?tab=repositorieshttps://github.com/fathi-fayez?tab=repositories"
              target="_blank"><i class="fa-brands fa-github" style="color: #4078c0"></i></a>
            <a href="https://www.linkedin.com/in/fathi-fayez-0416671a6/" target="_blank"><i
                class="fa-brands fa-linkedin" style="color: #0a66c2"></i></a>

            <a href="mailto:fathifayez155@gmail.com" target="_blank"><i class="fa-brands fa-google"
                style="color: #ea4335"></i></a>
          </div>
        </div>

        <!-- Footer Location -->
        <div class="col-lg-4 page-footer-column">
          <h4 class="text-uppercase mb-4"><i class="fa fa-map-pin me-2"></i>Location</h4>
          <p class="address">Egypt - Cairo</p>
        </div>

        <!-- Copyright -->
        <div class="col-lg-12 copyright-column">
          <small class="text-muted">Copyright © Fathi Fayez 2024</small>
        </div>
      </div>
    </div>
  </footer>
</template>
<!-- eslint-disable -->
<script>
export default {
  name: "Footer",
};
</script>
<!-- eslint-disable -->
<style scoped lang="scss">
.page-footer {
  background-color: black;
  color: white;
  padding-top: 100px;
  text-align: center;
}

.page-footer-column {
  margin-bottom: 3rem;
}

.copyright-column {
  margin-bottom: 1rem;
}

.address {
  color: #eee;
}

.social-icons {
  font-size: 34px;

  a {
    margin: 10px;
  }
}
</style>
