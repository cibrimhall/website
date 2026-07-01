---
widget: hero
headless: true
weight: 10
title:

design:
  background:
    color: "#ffffff"
  spacing:
    padding: ["0", "0", "0", "0"]

---

<style>
body {
  background-color: #ffffff !important;
}
.cb-hero {
  position: relative;
  left: 50%;
  right: 50%;
  margin-left: -50vw;
  margin-right: -50vw;
  width: 100vw;
  overflow: hidden;
  height: 640px;
}
.cb-hero__rect--blue {
  position: absolute;
  top: 0;
  right: 0;
  width: 50vw; /* reaches about to the middle of the page */
  height: 400px; /* 5/8 of the 640px hero height */
  background: #2c4a6e;
  z-index: 0;
}
.cb-hero__rect--yellow {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 46vw;
  height: 220px; /* taller than before */
  background: #e3ae43;
  z-index: 0;
}
.cb-hero__inner {
  position: relative;
  z-index: 1;
  max-width: 1000px;
  height: 100%;
  margin: 0 auto;
}
.cb-hero__text {
  position: relative;
  z-index: 2;
  max-width: 440px;
  padding: 70px 30px 0 40px;
}
.cb-hero__name {
  font-size: 2rem;
  font-weight: 700;
  margin: 0 0 6px;
  color: #222;
}
.cb-hero__role {
  font-size: 1.05rem;
  color: #555;
  margin: 0 0 20px;
}
.cb-hero__text p {
  font-size: 1.05rem;
  line-height: 1.7;
  color: #333;
}
.cb-hero__links {
  margin-top: 20px;
  font-size: 1rem;
}
.cb-hero__photo {
  position: absolute;
  z-index: 3;
  top: 50%;
  right: 20px;
  transform: translateY(-50%);
  width: 460px;
  height: 460px;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 15px 35px rgba(0,0,0,.2);
  background: #ddd; /* shows while the image loads, or if it 404s */
}
.cb-hero__photo img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}
@media (max-width: 900px) {
  .cb-hero {
    height: auto;
    min-height: 780px;
  }
  .cb-hero__photo {
    position: relative;
    top: auto;
    right: auto;
    transform: none;
    width: 220px;
    height: 220px;
    margin: 20px auto 0;
  }
  .cb-hero__text {
    max-width: none;
    padding: 50px 25px 0;
  }
  .cb-hero__rect--blue {
    width: 60vw;
    height: 260px;
  }
  .cb-hero__rect--yellow {
    width: 65vw;
    height: 110px;
  }
}
</style>

<div class="cb-hero">
  <div class="cb-hero__rect--blue"></div>
  <div class="cb-hero__rect--yellow"></div>
  <div class="cb-hero__inner">
    <div class="cb-hero__text">
      <p>I'm a Senior Lecturer in the School of Management and Governance at UNSW Business School. My research examines how managers and employees make decisions under uncertainty, with a focus on how they think about skill and luck, and the strategies they adopt to reach their goals. I combine lab studies, field experiments, and archival analysis to better understand why employees make the decisions they do. Before joining UNSW, I was a Postdoctoral Fellow in Behavioural Decision Making at UCLA.</p>
      <p class="cb-hero__links">
        <a href="https://scholar.google.com/citations?user=t0qL1FMAAAAJ&hl=en&oi=ao">Google Scholar</a> &nbsp;·&nbsp; <a href="mailto:c.brimhall@unsw.edu.au">c.brimhall@unsw.edu.au</a>
      </p>
    </div>
    <div class="cb-hero__photo">
      <img src="/uploads/craig-portrait.jpg" alt="Craig Brimhall">
    </div>
  </div>
</div>
