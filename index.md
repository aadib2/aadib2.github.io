---
layout: page
title: ""
permalink: /
---

<style>
.intro-container {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    gap: 30px;
    margin-bottom: 2rem;
}

.intro-container img {
    width: 180px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.15);
}

.intro-text {
    max-width: 600px;
}

.featured-img {
    width: 180px;
    padding: 5px;
}

@media (max-width: 768px) {
  .intro-container {
    flex-direction: column;
    text-align: center;
  }
}

  /* for featured image section at bottom */
.featured-gallery {
  display: flex;
  flex-wrap: wrap;
  gap: 32px;
  justify-content: center;
  margin-bottom: 2rem;
}
.featured-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  max-width: 220px;
}
.featured-item img {
  width: 210px;
  height: 140px;
  object-fit: cover;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.15);
}
.featured-item p {
  margin-top: 0.7em;
  font-size: 15px;
  text-align: center;
}

/* adapting for mobile screens */
@media (max-width: 768px) {
  .featured-gallery {
    flex-direction: column;
    align-items: center;
  }

}

.aboutme-container {
    display: flex;
    align-items: flex-start;
    margin-bottom: 2em;
}

.aboutme-img {
    width: 150px;
    height: 100px;
    border-radius: 8px;
    margin-right: 1em;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

/* Add this for vertical stacking and spacing */
.aboutme-container > div {
    display: flex;
    flex-direction: column;
    gap: 1em; /* space between paragraphs */
}

.aboutme-container p {
    margin: 0;
    line-height: 1.6;
    font-size: 1.05em;
}

</style>

<div class="intro-container">
  <img src="/assets/img/homepage-pic.jpg" alt="Aadi Bery Headshot" />
  <div class="intro-text">
    <h2>Hey, I'm Aadi!</h2>
    <b>Computer Science Student &nbsp;|&nbsp; Undergrad Researcher &nbsp;|&nbsp; SDSU AI Club CTO &nbsp;|&nbsp; BTT Fellow </b>
    <!-- this &nbsp above is non-breaking space in html --> 

  </div>
</div>

<h2>About Me:</h2>

<div class="aboutme-container">
  <img class="aboutme-img" src="/assets/img/sdsulogo.png" alt="SDSU logo" />
  <div>
  <p>
    I'm currently pursuing a <strong>B.S. in Computer Science</strong> with a <strong>minor in Math @ San Diego State University (SDSU)</strong>. I'm a curious, detail-oriented problem solver and collaborator who is passionate about
    applying <strong>data science, machine learning & AI, and software development techniques</strong>
    to tackle real-world challenges and automate workflows. I enjoy
    collaborating on interdisciplinary teams and continuously learning through
    hands-on projects, research, and leadership experiences.
  </p>

  <p>
    💡 Currently, I'm looking to leverage my knowledge and skills in a
    <strong>Summer 2026 Technical Internship</strong> where I can contribute to
    exciting and impactful real-world projects and be inspired alongside
    industry and research professionals.
  </p>

  <p>
    ⛰️ Outside of academics, I enjoy being out in nature, going on hiking
    trails, playing tennis or basketball, and spending time reading about
    interesting topics!
  </p>

  <p>
    🔥 Feel free to explore the site to learn more about my
    <a href="/experience/">experiences</a> and
    <a href="/projects/">projects</a> thus far! Or check the featured section below!
  </p>
  </div>

</div>


---

<h2> Featured 📷 </h2>

<div class="featured-gallery">
  <div class="featured-item">
    <img src="/assets/img/featured-pics/aas-pic.jpeg" alt="AAS-Alaska" />
    <p> June 2025: American Astronomical Society Conference for Summer Research 🪐</p>
  </div>
  <div class="featured-item">
    <img src="/assets/img/featured-pics/btt-zoom.png" alt="BTT MLF Last Day" />
    <p>July 2025: Break Through Tech ML Foundations Lab! 💪</p>
  </div>
  <div class="featured-item">
    <img src="/assets/img/featured-pics/aibootcamppic.jpg" alt="Sekeh Lab DL" />
    <p>July 2025: Attended SDSU Deep Learning Bootcamp hosted by Sekeh Lab! 🤖</p>
  </div>
  <div class='featured-item'>
    <img src='/assets/img/featured-pics/alum-panel.jpg' alt='CSSC Panel' />
    <p> February 2025: Organized STEM Alumni Panel as A.S. Sciences Representative 👔 </p>
  </div>
  <div class='featured-item'>
    <img src='/assets/img/featured-pics/glazer-endyr.jpeg' alt='Glazer EndOfYr' />
    <p> May 2025: SDSU Glazer Center End of Year Celebration for Launch program 🚀 </p>
  </div>
  <div class='featured-item'>
    <img src='/assets/img/featured-pics/volunteering.jpeg' alt='CSSC Panel' />
    <p> April 2025: Volunteering for Produce Good with SDSU Rotaract 🍋 </p>
  </div>
  <div class='featured-item'>
    <img src='/assets/img/featured-pics/exec pic at council horizontal.JPG' alt='CSSC Executive' />
    <p> October 2024: College of Sciences Student Council Executive Board 🧪 </p>
  </div>
  
</div>
