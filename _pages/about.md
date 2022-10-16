---
permalink: /about/
classes: wide
layout: single
title: "About"
author:
  name   : "Michael Potter"
  avatar : "/assets/images/bio-photo.jpg"
  bio    : "I am a second year Electronics Engineer with NSWC Corona in AR43. I specialize in Machine Learning topics, currently acting as the principal investigator for ISEA of the Future - NSWC Corona."
---

NSWC Corona Division has served as the Navy's independent assessment agent since 1964. With experience in gauging the Navy's warfighting capability, NSWC Corona is positioned as a leader in NAVSEA data analytics. Utilizing networked data environments, data analytics and visualization, and measurement technology to bridge the Navy's disparate data, Corona enables informed decision-making for the warfighter. 

NSWC Corona Technical Exchange Meeting offers a platform for organizations to present technological advancements and innovations. The primary interest areas for this Technical Exchange Meeting include: Assured Identity, Automation, MLOps, Security & Operations (DevSecOps), Fifth Generation Wireless (5G), Machine Learning & Artificial Intelligence (ML & AI), Industry 4.0, and Material Sciences.

# Meet The Team
/* Three columns side by side */
.column {
  float: left;
  width: 33.3%;
  margin-bottom: 16px;
  padding: 0 8px;
}
<style>
@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}

/* Add some shadows to create a card effect */
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

/* Some left and right padding inside the container */
.container {
  padding: 0 16px;
}

/* Clear floats */
.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: grey;
}

.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: #555;
}
</style>
<div class="row">
  <div class="column">
    <div class="card">
      <img src="{{ site.url }}{{ site.baseurl }}/assets/images/bio-photo.jpg" alt="Jane" style="width:100%">
      <div class="container">
        <h2>Jane Doe</h2>
        <p class="title">CEO &amp; Founder</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <img src="{{ site.url }}{{ site.baseurl }}/assets/images/bio-photo.jpg" alt="Mike" style="width:100%">
      <div class="container">
        <h2>Mike Ross</h2>
        <p class="title">Art Director</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <img src="{{ site.url }}{{ site.baseurl }}/assets/images/bio-photo.jpg" alt="John" style="width:100%">
      <div class="container">
        <h2>John Doe</h2>
        <p class="title">Designer</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
</div>
