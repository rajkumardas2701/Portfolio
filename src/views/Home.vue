<template>
  <div class="home sections home-page d-flex">
    <div class="background-section col-md-2"></div>
    <div class="background-section col-md-2"></div>
    <div class="background-section col-md-2"></div>
    <div class="background-section col-md-2"></div>
    <div class="background-section col-md-2"></div>
    <div class="main-content">
      <h1>
        Hi, I am
        <span>Rajkumar Das</span>
      </h1>
      <p>
        Software development should not be a secret process, when I take on a
        new project, I make it my goal to not only deliver a well crafted
        product but to also ensure that each stage of the process is fully
        communicated.
      </p>
      <div class="social-media d-flex">
        <div class="linkedIn">
          <a href="https://www.linkedin.com/in/dasrajkumar27/" target="_blank">
            <i class="fab fa-linkedin-in"></i>
          </a>
        </div>
        <div class="twitter mx-2">
          <a href="https://twitter.com/Rajkuma58621299" target="_blank">
            <i class="fab fa-twitter"></i>
          </a>
        </div>
        <div class="github">
          <a href="https://github.com/rajkumardas2701" target="_blank">
            <i class="fab fa-github"></i>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Home",
  components: {},
};
</script>
<style scoped>
.main-content {
  position: absolute;
  width: 70em;
  height: 20em;
  font-family: Nunito, sans-serif;
  font-weight: 900;
  margin: 17em 8em 0;
  color: #fff;
}

.fab {
  font-size: 20px;
}

.main-content h1 {
  font-size: 3.285rem;
}

.main-content p {
  font-size: 20px;
  color: #6f7588;
}
.main-content span {
  color: #037fff;
}

.social-media {
  justify-content: center;
}

.sections {
  position: absolute;
  width: 81%;
  right: 0;
  height: 100vh;
}

.social-media div {
  display: flex;
  border-radius: 50%;
  border: 3px solid #6f7588;
  width: 40px;
  height: 40px;
  justify-content: center;
  align-items: center;
  padding: 5px;
  cursor: pointer;
}
</style>
