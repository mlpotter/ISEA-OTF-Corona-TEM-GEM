---
permalink: /about/
classes: wide
layout: splash
title: "About"
author:
  name   : "Michael Potter"
  avatar : "/assets/images/bio-photo.jpg"
  bio    : "I am a second year Electronics Engineer with NSWC Corona in AR43. I specialize in Machine Learning topics, currently acting as the principal investigator for ISEA of the Future - NSWC Corona."
feature_row:
  - image_path: 
    title: "Pravin Naik"
    excerpt: "TBD"
    url: https://www.linkedin.com/in/pnaik98/
    btn_label: "More Info"
    btn_class: "btn--primary"
  - image_path: 
    title: "Ed Schuberg"
    excerpt: "TBD"
    url: https://www.linkedin.com/in/edward-schuberg/
    btn_label: "More Info"
    btn_class: "btn--primary"
  - image_path:
    title: "Michael Potter"
    excerpt: "TBD"
    url: https://github.com/mlpotter
    btn_label: "More Info"
    btn_class: "btn--primary"
  - image_path:
    title: "Nicole Chik"
    excerpt: "TBD"
    url: https://www.linkedin.com/in/nicoledumbroff/
    btn_label: "More Info"
    btn_class: "btn--primary"
---
<h2 style="text-align:center">About</h2>
NSWC Corona Division has served as the Navy's independent assessment agent since 1964. With experience in gauging the Navy's warfighting capability, NSWC Corona is positioned as a leader in NAVSEA data analytics. Utilizing networked data environments, data analytics and visualization, and measurement technology to bridge the Navy's disparate data, Corona enables informed decision-making for the warfighter. 

NSWC Corona Technical Exchange Meeting offers a platform for organizations to present technological advancements and innovations. The primary interest areas for this Technical Exchange Meeting include: Assured Identity, Automation, MLOps, Security & Operations (DevSecOps), Fifth Generation Wireless (5G), Machine Learning & Artificial Intelligence (ML & AI), Industry 4.0, and Material Sciences.

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}

html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

.column {
  float: left;
  width: 33.3%;
  margin-bottom: 16px;
  padding: 0 8px;
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  margin: 8px;
}

.container {
  padding: 0 16px;
}

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

.img {
    float: center;
    width:  100px;
    height: 100px;
    object-fit: cover;
}
  
@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}
</style>
</head>
<body>

<h2 style="text-align:center">Our Team</h2>
<div class="row">
  <div class="column">
    <div class="card">
      <img src="{{ site.url }}{{ site.baseurl }}/assets/images/bio-photo.jpg" alt="Ed">
      <div class="container">
        <h2>Ed Schuberg</h2>
        <p class="title">Co Principal Investigator</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>jane@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <img src="{{ site.url }}{{ site.baseurl }}/assets/images/bio-photo.jpg" alt="Pravin">
      <div class="container">
        <h2>Pravin Naik</h2>
        <p class="title">Co Principal Investigator</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>mike@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
  
  <div class="column">
    <div class="card">
      <img src="{{ site.url }}{{ site.baseurl }}/assets/images/MichaelPotter_ProfilePicture.JPG" alt="Nicole">
      <div class="container">
        <h2>Nicole Chik</h2>
        <p class="title">Co Principal Investigator</p>
        <p>Some text that describes me lorem ipsum ipsum lorem. I love apple pie my best favoriate card</p>
        <p>john@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
</div>
<div class="row">
  <div class="column">
    <div class="card">
      <img src="{{ site.url }}{{ site.baseurl }}/assets/images/MichaelPotter_ProfilePicture.JPG" alt="Michael" width="100px" height="100px">
      <div class="container">
        <h2>Michael Potter</h2>
        <p class="title">Principal Investigator</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>jane@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
</div>
</body>
</html>
