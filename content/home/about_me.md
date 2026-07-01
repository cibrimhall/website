---
widget: blank
headless: true
weight: 10
title:

design:
  columns: '1'
  background:
    color: "#ffffff"
  spacing:
    padding: ["0", "0", "0", "0"]

---

<style>
.cb-hero {
  position: relative;
  overflow: hidden;
  padding: 70px 20px;
}
.cb-hero__square--blue {
  position: absolute;
  top: -50px;
  right: -50px;
  width: 220px;
  height: 220px;
  background: #2c4a6e;
  z-index: 0;
}
.cb-hero__square--yellow {
  position: absolute;
  bottom: 30px;
  left: 20px;
  width: 70px;
  height: 70px;
  background: #e3ae43;
  z-index: 0;
}
.cb-hero__row {
  position: relative;
  z-index: 1;
  max-width: 900px;
  margin: 0 auto;
  display: flex;
  align-items: center;
  gap: 50px;
}
.cb-hero__text {
  flex: 1 1 55%;
}
.cb-hero__text h1 {
  font-size: 2rem;
  margin: 0 0 6px;
}
.cb-hero__text .cb-hero__role {
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
  flex: 0 0 260px;
}
.cb-hero__photo img {
  width: 260px;
  height: 260px;
  object-fit: cover;
  border-radius: 8px;
  display: block;
}
@media (max-width: 700px) {
  .cb-hero__row {
    flex-direction: column-reverse;
    gap: 30px;
  }
  .cb-hero__photo, .cb-hero__photo img {
    width: 200px;
    height: 200px;
  }
  .cb-hero__square--blue {
    width: 140px;
    height: 140px;
  }
}
</style>

<div class="cb-hero">
  <div class="cb-hero__square--blue"></div>
  <div class="cb-hero__square--yellow"></div>
  <div class="cb-hero__row">
    <div class="cb-hero__text">
      <h1>Craig Brimhall</h1>
      <p class="cb-hero__role">Senior Lecturer, School of Management and Governance, UNSW Business School</p>
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
