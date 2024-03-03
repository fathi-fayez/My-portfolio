<template>
  <div class="my-work container" id="myworks-section">
    <h1>My Work</h1>
    <div class="row justify-content-center">
      <!-- project -->
      <div class="project-container col-md-3 p-0 m-2 rounded">
        <a
          href="https://e-commerce-website-375i.vercel.app/"
          target="_blank"
          class="btn p-0"
        >
          <div class="project card mb-4">
            <img
              src="../assets/project-logo-1.png"
              class="card-img-top"
              alt="project-image"
            />
            <h5 class="card-title p-3">E-commerce</h5>
          </div>
        </a>
        <!-- source code link -->
        <a
          class="github-icon"
          href="https://github.com/fathi-fayez/e-commerce-website"
          target="_blank"
          title="View source code"
          ><i class="fa-brands fa-github" style="color: #4078c0"></i
        ></a>
      </div>
      <!-- project -->
      <div class="project-container col-md-3 p-0 m-2">
        <a
          href="https://car-shop-one-mu.vercel.app/"
          target="_blank"
          class="btn p-0"
        >
          <div class="project card mb-4">
            <img
              src="../assets/project-logo-2.png"
              class="card-img-top"
              alt="project-image"
            />
            <h5 class="card-title p-3">Car shop</h5>
          </div>
        </a>
        <!-- source code link -->
        <a
          class="github-icon"
          href="https://github.com/fathi-fayez/car-shop"
          target="_blank"
          title="View source code"
          ><i class="fa-brands fa-github" style="color: #4078c0"></i
        ></a>
      </div>
      <!-- project -->
      <div class="project-container col-md-3 p-0 m-2">
        <a
          href="https://admin-dashboard-xi-lime.vercel.app/"
          target="_blank"
          class="btn p-0"
        >
          <div class="project card mb-4">
            <img
              src="../assets/project-logo-6.png"
              class="card-img-top"
              alt="project-image"
            />
            <h5 class="card-title p-3">Admin dashboard</h5>
          </div>
        </a>
        <!-- source code link -->
        <a
          class="github-icon"
          href="https://github.com/fathi-fayez/admin-dashboard"
          target="_blank"
          title="View source code"
          ><i class="fa-brands fa-github" style="color: #4078c0"></i
        ></a>
      </div>
      <!-- project -->
      <div class="project-container col-md-3 p-0 m-2">
        <a
          href="https://european-weather-forecast.vercel.app/"
          target="_blank"
          class="btn p-0"
        >
          <div class="project card mb-4">
            <img
              src="../assets/project-logo-3.png"
              class="card-img-top"
              alt="project-image"
            />
            <h5 class="card-title p-3">Weather forecast</h5>
          </div>
        </a>
        <!-- source code link -->
        <a
          class="github-icon"
          href="https://github.com/fathi-fayez/European-Weather-Forecast-project"
          target="_blank"
          title="View source code"
          ><i class="fa-brands fa-github" style="color: #4078c0"></i
        ></a>
      </div>
      <!-- project -->
      <div class="project-container col-md-3 p-0 m-2">
        <a
          href="https://todo-app-vue-rho.vercel.app/"
          target="_blank"
          class="btn p-0"
        >
          <div class="project card mb-4">
            <img
              src="../assets/project-logo-4.png"
              class="card-img-top"
              alt="project-image"
            />
            <h5 class="card-title p-3">Todo App</h5>
          </div>
        </a>
        <!-- source code link -->
        <a
          class="github-icon"
          href="https://github.com/fathi-fayez/todo-App-vue"
          target="_blank"
          title="View source code"
          ><i class="fa-brands fa-github" style="color: #4078c0"></i
        ></a>
      </div>
      <!-- project -->
      <div class="project-container col-md-3 p-0 m-2">
        <a
          href="https://travel-app-blond.vercel.app/"
          target="_blank"
          class="btn p-0"
        >
          <div class="project card mb-4">
            <img
              src="../assets/project-logo-5.png"
              class="card-img-top"
              alt="project-image"
            />
            <h5 class="card-title p-3">Travel App</h5>
          </div>
        </a>
        <!-- source code link -->
        <a
          class="github-icon"
          href="https://github.com/fathi-fayez/travel-app"
          target="_blank"
          title="View source code"
          ><i class="fa-brands fa-github" style="color: #4078c0"></i
        ></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "myWorks",
  data() {
    return {
      works: [
        {
          title: "Project 1",
          description:
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit.",
          image: "https://via.placeholder.com/300",
          link: "#",
        },
        {
          title: "Project 2",
          description:
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit.",
          image: "https://via.placeholder.com/300",
          link: "#",
        },
        {
          title: "Project 3",
          description:
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit.",
          image: "https://via.placeholder.com/300",
          link: "#",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
.my-work {
  padding-top: 100px;
  padding-bottom: 100px;
  h1 {
    margin-bottom: 40px;
  }
  .project-container {
    width: 300px;
    height: 200px;
    transition: 0.5s;
    box-shadow: 0px 12px 20px 0px rgb(0 0 0 / 13%),
      0px 2px 4px 0px rgb(0 0 0 / 12%);
    position: relative;
    overflow: hidden;
  }
  .project-container:hover {
    .github-icon {
      bottom: 3px;
    }
  }
  .project {
    overflow: hidden;
    position: relative;
  }
  .project::before {
    content: "";
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: rgb(3 169 244 / 18%);
    width: 0;
    height: 0;
    transition: 3s;
    opacity: 0;
    z-index: 2;
  }
  .project:hover::before {
    animation: flashing 0.8s;
  }
  .project:hover {
    h5 {
      color: rgb(42, 13, 235);
    }
  }
  .github-icon {
    position: absolute;
    left: 10px;
    bottom: -50px;
    font-size: 35px;
    transition: 0.3s;
  }
  .github-icon:hover {
    font-size: 40px;
  }
}
@keyframes flashing {
  0%,
  40% {
    opacity: 1;
  }

  100% {
    opacity: 0;
    width: 200%;
    height: 200%;
  }
}
</style>
