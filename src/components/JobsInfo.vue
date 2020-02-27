<template>
  <div>
    <div class="about" id="about">
      <span class="label">about me...</span>
    </div>
    <div class="resume">
      <div class="education">
        <div class="container">
          <span class="cat-label">EDUCATION</span>
          <div class="university">
            <span class="label">GRADUATE CERTIFICATE IN INTERACTION DESIGN FOR DIGITAL ARTIFACTS</span>
            <span>C.E.S.A.R School  – Brazil, ongoing.</span>
          </div>
          <div class="university">
            <span class="label">ADVANCED DIPLOMA IN GRAPHIC DESIGN</span>
            <span>UniFBV Devry – Brazil, completed 2016.</span>
          </div>
        </div>
      </div>
      <div class="working-experiences">
        <div class="container">
          <span class="cat-label">WORKING EXPERIENCES</span>
          <div class="experience">
            <span class="label">Melhor Comunicação - UX Lead and Department Coordinator</span>
            <span>(November  2018 – November 2019)</span>
            <ul>
              <li>Led the Department of Digital Products with 2 teams (web team and a big project team)</li>
              <li>Led the Department of Digital Products with 2 teams (web team and a big project team)</li>
              <li>Led the Department of Digital Products with 2 teams (web team and a big project team)</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="professional-skills">
        <div class="container">
          <span class="cat-label">PROFESSIONAL SKILLS</span>
          <div class="skill">
            <p>I have experience working with teams to brainstorm and whiteboard concepts. I can create wireframes at varying levels of fidelity, and enjoy prototyping ideas.</p>
            <p>I have some front-end coding experience and enjoy working with developers to build ideas out. I have worked with distributed teams using version control system (Git).</p>
            <p>Designing tools such as UX, ideation and workflows interaction and UI design. Prototyping with Sketch, Adobe XD and using almost all softwares of Adobe Creative Suite;</p>
            <p>User Research tools such as interviews and surveys, usability and concept testing and System Usability Scale (SUS);</p>
            <p>I’m strong with some development tools such HTML, CSS3 and JavaScript ES6. I’m familiar with PHP, MySQL, Linux Shell and Cloud Hosting (Digital Ocean with Runcloud or Cloudrun).</p>
          </div>
        </div>
      </div>
      <div class="certifications">
        <div class="container">
          <span class="cat-label">CERTIFICATIONS</span>
          <div class="certificate">
            <span class="label">UX Course for Web Designers</span>
            <span>Udemy - UCJ15AU546 – 2019</span>
          </div>
          <div class="certificate">
            <span class="label">Complete Web Design</span>
            <span>Origamid – AFC6C057 – 2019</span>
          </div>
          <div class="certificate">
            <span class="label">WordPress as CMS</span>
            <span>Origamid – 53FEFEC7 – 2019</span>
          </div>
          <div class="certificate">
            <span class="label">Matte Compositing with NUKE</span>
            <span>Magno Borgo – 2017</span>
          </div>
          <div class="certificate">
            <span class="label">JLPT - Japanese Language Proficiency Test N5</span>
            <span>Basic Level – 2013</span>
          </div>
          <div class="certificate">
            <span class="label">3D Modelling, Rigging, Animation and Render with Autodesk 3DS Max</span>
            <span>S.A.G.A – 2010;</span>
          </div>
          <div class="certificate">
            <span class="label">Basic Video Editing with Adobe Premiere</span>
            <span>S.A.G.A – 2010</span>
          </div>
          <div class="certificate">
            <span class="label">Matte Compositing with Autodesk Combustion</span>
            <span>S.A.G.A – 2010</span>
          </div>
        </div>
      </div>
      <div class="languages">
        <div class="container">
          <span class="cat-label">LANGUAGES</span>
          <div class="language">
            <span class="label">English</span>
            <span>Upper-Intermediate Level</span>
          </div>
          <div class="language">
            <span class="label">Portuguese</span>
            <span>Fluent / Native Level</span>
          </div>
          <div class="language">
            <span class="label">Japanese</span>
            <span>Basic Level</span>
          </div>
        </div>
      </div>
      <div class="latest-projects">
        <div class="container">
          <span class="cat-label">LATEST PROJECTS</span>
          <div class="project">
            <span class="label">Melhor Comunicação (2019)</span>
            <span>visual design, ux lead and front-end development</span> -
            <a
              class="nav__link"
              href="https://melhorcom.com.br/"
              target="_blank"
            >https://melhorcom.com.br/</a>
          </div>
          <div class="project">
            <span class="label">Veneza Water Park (2019)</span>
            <span>ux lead and front-end development</span> -
            <a
              class="nav__link"
              href="https://melhorcom.com.br/"
              target="_blank"
            >https://venezawaterpark.com.br/</a>
          </div>
          <div class="project">
            <span class="label">ITCBio (2019)</span>
            <span>ux lead and front-end development</span> -
            <a class="nav__link" href="https://#.com.br/" target="_blank">https://#.com.br/</a>
          </div>
          <div class="project">
            <span class="label">Novo Nascer (2019)</span>
            <span>ux lead and front-end development</span> -
            <a
              class="nav__link"
              href="https://www.novonascer.com.br/"
              target="_blank"
            >https://www.novonascer.com.br/</a>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: "jobs-info"
};
</script>

<style scoped>
.latest-projects, .education, .professional-skills, .languages, .working-experiences {
  margin: 2rem 0;
}
.cat-label {
  font-size: 0.6rem;
  font-weight: 400;
  text-transform: uppercase;
  margin-top: 1.5rem;
  padding-bottom: 0.5rem;
  width: 100%;
  border-bottom: 1px solid var(--color-base-1);
}
.latest-projects .project, .languages .language, .certifications .certificate, .working-experiences .experience, .education .university, .professional-skills .skill {
  padding-top: 1rem;
}
/* .about {
    margin-top: 6rem;
    margin-bottom: 1rem;
    font-size: 0.6rem;
    font-weight: 400;
    text-transform: uppercase;
    background: var(--color-base-1);
    padding: 1rem .8rem .5rem;
} */
.about {
    font-size: 3rem;
    font-weight: 700;
    padding: 4rem 0rem 0rem;
    margin: 0;
    color: var(--color-base-1);
    letter-spacing: -0.01em;
    text-align: left;
}

@media (min-width: 860px) {
  .about .container {
      padding: 0 6rem;
  }
}
.about .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
}
.resume .container {
  padding: 0 2rem;
}
.resume {
    margin: 0;
    border-left: 0;
    border-right: 0;
    /* border-top: 1px solid var(--color-base-1); */
}
.skill p {
    line-height: 1.5;
    font-size: 0.9rem;
    padding-right: 5px;
}
</style>
