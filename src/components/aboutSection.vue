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
            <p>
              I’m a Front-End Developer with over a year of experience building responsive, user-friendly
              websites. I’m passionate about UI effects, animations, and creating smooth, dynamic user experiences.


            </p>
            <p>
              I’m detail-oriented, a strong problem solver, and enjoy working on creative, ambitious projects with
              positive teams. Always learning and growing, I stay up-to-date with the latest in front-end development.
            </p>

            <a class="btn btn-primary btn-xl mt-4"
              href="https://drive.google.com/uc?export=download&id=1MQm1Z5RqfU1Gke1JC9TsPYRwkGuLT2nH"
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