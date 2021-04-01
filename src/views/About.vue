<template>
  <div class="about main-section">
    <h1 class="ml-4">ABOUT ME</h1>
    <div class="home sections home-page d-flex">
      <div class="background-section col-md-2"></div>
      <div class="background-section col-md-2"></div>
      <div class="background-section col-md-2"></div>
      <div class="background-section col-md-2"></div>
      <div class="background-section col-md-2"></div>
      <div class="main-content">
        <div>
          <h1>ABOUT ME</h1>
        </div>
        <div class="inner-section">
          <div class="middle-section"></div>
        </div>
        <div class="details d-flex">
          <!-- <div class="image-section"></div> -->
          <div class="details-section">
            <h2>I am <span>Rajkumar Das</span></h2>
            <p>
              Rare communication with clients throughout the development stage
              results in a final product that fails to reach the goal sought by
              the customer and end user. <br /><br />For this reason I decided
              to utilize a completely different development pattern that focuses
              on highly focused communication and transparent design patterns.
              My goal is to ensure whenever I take on a project not only do I
              work to craft the application according to the client's
              specifications, I give daily updates to ensure that the project is
              aligning properly with the client's goals. The end result is the
              right product, delivered on time, and on budget.
            </p>
            <div class="partial name d-flex mb-2">
              <div class="first">
                <span>Title</span>
              </div>
              <div class="second-partial">
                <p>: Mr.</p>
              </div>
            </div>
            <div class="partial name d-flex">
              <div class="first">
                <span>Full Name</span>
              </div>
              <div class="second-partial">
                <p>: Rajkumar Anilkumar Das</p>
              </div>
            </div>
            <div class="partial nationality my-2 d-flex">
              <div class="first">
                <span>Nationality</span>
              </div>
              <div class="second-partial">
                <p>: Indian</p>
              </div>
            </div>
            <div class="partial language d-flex">
              <div class="first">
                <span>Languages </span>
              </div>
              <div class="second-partial">
                <p>: English, Hindi, Marathi</p>
              </div>
            </div>
            <div class="partial address my-2 d-flex">
              <div class="first">
                <span>Address</span>
              </div>
              <div class="second-partial">
                <p>
                  : 8th Main, 2nd Main, ITI Layout, Yellukunte, HSR Layout,
                  Bengaluru, Karnataka, India-560068
                </p>
              </div>
            </div>
            <div class="partial frelance d-flex">
              <div class="first">
                <span>Full-Time</span>
              </div>
              <div class="second-partial">
                <p>: Available</p>
              </div>
            </div>
            <a
              class="cv-download ml-2 mt-2"
              href="https://docs.google.com/document/d/1pYtFyfdhIBRSoFMfrPpHNNsVHv6OMmCIr1qHqNyzwdQ/edit?usp=sharing"
              target="_blank"
            >
              VIEW RESUME
            </a>
          </div>
        </div>
        <div class="services">
          <h1>SERVICES</h1>
        </div>
        <div class="inner-section new-section">
          <div class="middle-section"></div>
        </div>
        <div class="service-section mt-4">
          <div class="front-end grid-section">
            <i class="fab fa-accusoft"></i>
            <h5>Web Design</h5>
            <div class="empty-div"></div>
            <div class="description">
              <p>
                This is mainly achieved using Bootstrap, HTML5, and CSS3. The
                development includes the use of media queries, font-awesome
                icons, and google fonts. The website is designed for various
                screen sizes including Desktop, Tab, and Mobile screen sizes.
              </p>
            </div>
          </div>
          <div class="back-end grid-section">
            <i class="fab fa-react"></i>
            <h5>Web Development(Front End)</h5>
            <div class="empty-div"></div>
            <div class="description">
              <p>
                I majorly develop single-page applications using Javascript and
                its frame-work of React.
              </p>
            </div>
          </div>
          <div class="articles grid-section">
            <i class="fas fa-server"></i>
            <h5>Web Development(Backend End)</h5>
            <div class="empty-div"></div>
            <div class="description">
              <p>
                On the Server-side (also know as Back-end), I specialize in Ruby
                and its frame-work of Ruby on Rails. The services are developed
                using relational databases like Postgress, SQLite.
              </p>
            </div>
          </div>
        </div>
        <div class="services">
          <h1>REVIEWS</h1>
        </div>
        <div class="inner-section new-section">
          <div class="middle-section"></div>
        </div>
        <div class="reviews-section">
          <div class="review-item">
            <p>
              I had the opportunity to work with Rajkumar Das during my time at
              Microverse. He was a member of my stand-up team. He is a very
              collaborative individual and openly shares his opinion about every
              challenge we had in the stand-ups. I greatly admire his leadership
              and communication skills. He always endeavors to make all the
              necessary communications. Besides that, he has great technical
              capabilities and always tries to understand concepts to depths. He
              would always create time for every individual in the team in case
              one needed support. Any team would be glad to have him as a member
            </p>
            <h5>
              BY:
              <span>
                <a
                  href="https://www.linkedin.com/in/sunday-alican-odong/"
                  target="_blank"
                >
                  Sunday Odong
                </a>
              </span>
            </h5>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.image-section {
  margin-top: 20px;
  background-image: url("../../public/PIC.jpeg");
  height: 32em;
  width: 30em;
  background-size: cover;
  background-repeat: no-repeat;
}

.details-section {
  font-family: Nunito, sans-serif;
  margin-top: 20px auto;
  width: 90%;
  padding-right: 10px;
}

.details-section p {
  font-size: 16px;
  color: #6f7588;
}

.details-section span {
  color: #0d7dfa;
}

.partial span,
.partial h5 {
  color: #a0aec0;
  font-size: 20px;
}

.partial h5 {
  margin-top: 4px;
}

.partial .first {
  width: 35%;
  display: flex;
  justify-content: flex-start;
  flex: 1;
  overflow-x: auto;
}

.second-partial {
  flex: 3;
  display: flex;
  justify-content: flex-start;
  overflow-x: auto;
}

.partial {
  width: 100%;
  height: 30px;
  background-color: #151621;
  padding: 0 20px;
  justify-content: flex-start;
}

.cv-download {
  background-color: #0d7dfa;
  height: 50px;
  width: 150px;
  display: flex;
  justify-content: center;
  align-items: center;
  cursor: pointer;
  color: #edf2f7;
  border: none;
  font-size: 14px;
}

.services {
  margin-top: 40px;
}

.new-section {
  margin-top: 100px;
}

.service-section {
  font-family: Nunito, sans-serif;
  width: 100%;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
}

.grid-section {
  background-color: #191d2b;
  border: 1px solid #2e344e;
  border-top: 4px solid #2e344e;
  cursor: pointer;
  color: #fff;
  padding-top: 5px;
}

.grid-section :hover {
  color: #fff;
  transition: ease;
}

.fa-accusoft,
.fa-react,
.fa-server {
  color: #0d7dfa;
  margin: 5px 0;
  font-size: 44px;
}

.empty-div {
  width: 4em;
  height: 2.5px;
  margin-left: 15px;
  background-color: #2e344e;
}

.description {
  padding: 10px;
  color: #a0aec0;
  font-size: 14px;
}

.reviews-section {
  display: flex;
  margin-top: 20px;
  max-height: 150px;
  overflow-x: auto;
  cursor: pointer;
  font-family: Nunito, sans-serif;
  color: #a0aec0;
}

.reviews-section::-webkit-scrollbar {
  width: 0;
}

.second-partial::-webkit-scrollbar {
  width: 0;
}

.partial .first::-webkit-scrollbar {
  width: 0;
  height: 0;
}

.review-item {
  min-width: 450px;
  height: 150px;
  background-color: #191d2b;
  border-left: 4px solid #2e344e;
  margin-right: 30px;
  padding: 10px;
  font-size: 14px;
}

.review-item span {
  color: #0d7dfa;
}

.back-end {
  margin: 0 10px;
}
@media only screen and (max-width: 1024px) {
  .details {
    flex-direction: column;
    align-self: center;
  }

  /* .details .image-section {
    width: 90%;
    height: 500px;
    margin: auto;
  } */

  .details .details-section {
    width: 90%;
    margin: auto;
  }

  .service-section {
    display: flex;
    flex-direction: column;
  }

  .grid-section {
    width: 100%;
    margin: auto;
    margin-bottom: 10px;
  }
  .partial .first span {
    font-size: 13px;
  }
  .partial .first {
    display: flex;
    align-items: center;
  }
}
</style>
