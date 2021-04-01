<template>
  <div class="about main-section">
    <h1 class="ml-4">MY SKILLS</h1>
    <div class="home sections home-page d-flex">
      <div class="background-section col-md-2"></div>
      <div class="background-section col-md-2"></div>
      <div class="background-section col-md-2"></div>
      <div class="background-section col-md-2"></div>
      <div class="background-section col-md-2"></div>
      <div class="main-content">
        <div>
          <h1>MY SKILLS</h1>
        </div>
        <div class="inner-section">
          <div class="middle-section"></div>
        </div>
        <div class="skills-section">
          <div class="first-section">
            <h5>HTML5</h5>
            <div class="inner-skills">
              <div class="percentage">95%</div>
              <div class="inner-section-html">
                <div class="middle-section-html"></div>
              </div>
            </div>
          </div>
          <div class="second-section">
            <h5>CSS</h5>
            <div class="inner-skills">
              <div class="percentage">90%</div>
              <div class="inner-section-css">
                <div class="middle-section-css"></div>
              </div>
            </div>
          </div>
        </div>
        <div class="skills-section my-2">
          <div class="first-section">
            <h5>Ruby</h5>
            <div class="inner-skills">
              <div class="percentage">80%</div>
              <div class="inner-section-html">
                <div class="middle-section-html ruby"></div>
              </div>
            </div>
          </div>
          <div class="second-section">
            <h5>Ruby on Rails</h5>
            <div class="inner-skills">
              <div class="percentage">85%</div>
              <div class="inner-section-css">
                <div class="middle-section-css rails"></div>
              </div>
            </div>
          </div>
        </div>
        <div class="skills-section">
          <div class="first-section">
            <h5>Javascript</h5>
            <div class="inner-skills">
              <div class="percentage">80%</div>
              <div class="inner-section-html">
                <div class="middle-section-html ruby"></div>
              </div>
            </div>
          </div>
          <div class="second-section">
            <h5>React &#38; Redux</h5>
            <div class="inner-skills">
              <div class="percentage">80%</div>
              <div class="inner-section-css">
                <div class="middle-section-css ruby"></div>
              </div>
            </div>
          </div>
        </div>
        <div class="resume-section">
          <h1>RESUME</h1>
        </div>
        <div class="inner-section resume-section-div">
          <div class="middle-section"></div>
        </div>
        <div class="working-experience">
          <i class="fas fa-briefcase"></i>
          <h3>Working Experience</h3>
        </div>
        <div class="experience-section">
          <div class="dummy-div"></div>
          <div class="left-section">
            <span>February, 2020– Present</span>
          </div>
          <div class="right-section">
            <h5>Full Stack Web Developer</h5>
            <span>Personal projects</span>
            <p>
              <b><i>Phaser Game</i></b> — Endless runner game with a theme to
              collect coins and compete with rest. <br />Built with:
              (JavaScript, Jest, Phaser 3 framework) <br /><br /><b
                ><i>Twitter Bot</i></b
              >
              — The bot connects to Twitter API to get a list of your followers,
              help you follow someone, post COVID updates, festivals, and jobs
              nearby on your twitter handle. Built with: (Ruby, Rspec, Twitter
              API) <br /><br /><b><i>Tic-Tac-Toe</i></b> — The traditional game
              which can be played on browser by clicking on the empty places on
              the board. It has an option to either end the game or restart
              after every result. Built with: (Javascript, HTML5, CSS3)
            </p>
          </div>
        </div>
        <div class="experience-section">
          <div class="dummy-div"></div>
          <div class="left-section">
            <span>October 2019 - Present</span>
          </div>
          <div class="right-section">
            <h5>Support Escalation Engineer</h5>
            <span>Microsoft - Bengaluru, India</span>
            <p>
              De-escalating critical issues by a regular intervention.
              <br />Trained multiple partners on MS Cloud Services (Teams/Skype
              for Business).
            </p>
          </div>
        </div>
        <div class="experience-section">
          <div class="dummy-div"></div>
          <div class="left-section">
            <span>January 2018 - October 2019</span>
          </div>
          <div class="right-section">
            <h5>Technical Advisor</h5>
            <span>Microsoft - Bengaluru, India</span>
            <p>
              Led team of 20 people and ensured they have Technical skills and
              meet their KPI. <br />Handled executive escalations and led MS
              Team’s readiness program for all the suppliers.
            </p>
          </div>
        </div>
        <div class="working-experience">
          <i class="fas fa-book"></i>
          <h3>Educational Qualifications</h3>
        </div>
        <div class="experience-section">
          <div class="dummy-div"></div>
          <div class="left-section">
            <span>February 2020 - Present</span>
          </div>
          <div class="right-section">
            <h5>Full-Stack Web Development</h5>
            <span>Microverse</span>
            <p>
              At Microverse, I am Learning full-stack Web Development in Ruby,
              Ruby on Rails, Javascript, React & Redux, MYSQL, HTML, and CSS.
              Microverse also ensures that students have professional skills
              besides technical skills. These soft skills include remote and
              pair programming among others.
            </p>
          </div>
        </div>
        <div class="experience-section">
          <div class="dummy-div"></div>
          <div class="left-section">
            <span>2009 - 2013</span>
          </div>
          <div class="right-section">
            <h5>B.E. in Computers</h5>
            <span>Terna Engineering College, Mumbai University</span>
            <p>
              Completed my bachelors of engineering in computers with first
              class. <br />Participated in a dance competition for resonance
              event in Terna Engineering College. <br />Participated in
              volleyball during sports days in my college. <br />Participated in
              Antarang, where I had a role to play and a traditional dance
              performance. <br />An active member of the computer society of
              India in my college and volunteered for various events.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.skills-section {
  display: flex;
}

.first-section,
.second-section {
  text-align: start;
  padding: 5px 0;
  margin-top: 5px;
  flex: 1;
  color: #a1a9ac;
}

.inner-skills {
  display: flex;
  font-size: 18px;
  font-family: Nunito, sans-serif;
  align-items: center;
  background-color: #151621;
  width: 100%;
}

.inner-section-html,
.inner-section-css {
  width: 89%;
  background-color: #2e344e;
  height: 7px;
  margin-left: 10px;
}

.middle-section-html,
.middle-section-css {
  width: 95%;
  background-color: #0d7dfa;
  height: 7px;
}

.middle-section-css {
  width: 90%;
}

.javascript {
  width: 70%;
}

.react {
  width: 50%;
}

.ruby {
  width: 80%;
}

.rails {
  width: 85%;
}

.resume-section {
  margin-top: 50px;
}

.resume-section-div {
  margin-top: 120px;
}

.working-experience {
  font-family: Nunito, sans-serif;
  display: flex;
  font-size: 30px;
  align-items: center;
  color: #fff;
  margin: 10px 0;
}

.working-experience h3 {
  margin-top: 18px;
  margin-left: 10px;
}

.experience-section {
  font-family: Nunito, sans-serif;
  display: flex;
  font-size: 16px;
  padding: 2px 20px;
  border-left: 3px solid #2e344e;
  position: relative;
}

.experience-section .right-section {
  text-align: left;
  flex: 3;
  color: #a2a79d;
}

.experience-section h5 {
  color: #0d7dfa;
  font-size: 27px;
}

.experience-section span {
  color: #fff;
}

.experience-section p {
  margin-top: 10px;
}

.experience-section .left-section {
  text-align: left;
  flex: 1;
  color: #a2a79d;
}

.dummy-div {
  position: absolute;
  width: 15px;
  height: 15px;
  border: 3px solid #2e344e;
  border-radius: 50%;
  top: 0;
  left: 0;
  margin-top: 5px;
  margin-left: -9px;
  background-color: #10121b;
}

@media only screen and (max-width: 1024px) {
  .skills-section {
    display: flex;
    flex-direction: column;
  }
  .inner-skills {
    width: 90%;
  }
}

@media only screen and (max-width: 780px) {
  .experience-section {
    flex-direction: column;
  }
}
</style>
