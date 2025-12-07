<!-- eslint-disable -->
<template>
  <div class="about" id="about-section">
    <div class="container">
      <h1>About Me</h1>
      <div class="row align-items-center">
        <!-- Photo Section -->
        <div class="col-lg-5 col-md-6 text-center">
          <img src="../assets/images/about_me_photo.png" alt="Personal Photo" class="personal-photo img-fluid" />
        </div>
        <!-- Text Section -->
        <div class="col-lg-7 col-md-6 text-center">
          <div class="about-text">
            <p>I'm Fathi, a web developer driven by the excitement of turning business ideas into real, usable
              products. I chose the web because it gives me the freedom to build, test, and bring ideas to life. I love
              working on challenges that push me to grow and learn something new every day. If you have an idea you want
              to bring to life, let’s build it together.</p>

            <a class="btn btn-primary btn-xl mt-4"
              href="https://drive.google.com/uc?export=download&id=1i9AryxobKkiPFh0shUTwHxqIX_S1Qf5c"
              download="Fathi Fayez-Resume.pdf">Download Resume</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<!-- eslint-disable -->
<script>
export default {
  name: "AboutSection",
};
</script>
<!-- eslint-disable -->
<style scoped lang="scss">
.about {
  background: white;
  padding: 80px 0;
  text-align: center;

  h1 {
    font-size: 2.5rem;
    margin-bottom: 40px;
    color: #333;
  }

  .container {
    max-width: 1200px;
  }

  .personal-photo {
    max-width: 100%;
    height: auto;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
    max-height: 400px;
    object-fit: cover;
  }

  .personal-photo:hover {
    transform: scale(1.05);
  }

  .about-text {
    padding: 20px;

    p {
      font-size: 1.1rem;
      color: #555;
      line-height: 1.8;
      margin-bottom: 20px;
    }

    .btn-primary {
      background-color: #007bff;
      border: none;
      padding: 15px 40px;
      font-size: 1.1rem;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }

    .btn-primary:hover {
      background-color: #0056b3;
    }
  }

  @media (max-width: 767px) {
    .personal-photo {
      margin-bottom: 30px;
      max-width: 250px;
    }

    .about-text {
      padding: 0;
    }

    .row {
      flex-direction: column;
    }
  }
}
</style>