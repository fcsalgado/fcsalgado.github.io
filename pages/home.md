---
layout: home
title: 
description: 


background: /assets/theme/images/landscape.png
permalink: /
---

<title>Image and Description Layout</title>
<style>
  .container {
    display: flex;
    align-items: center; /* Center align horizontally */
    text-align: center; /* Center align text */
  }
  .image {
    flex: 1;
  }
  .image img {
    width: 300px; /* Adjust width as needed */
    height: auto; /* Maintain aspect ratio */
    border-radius: 50%; /* Make the image round */
  }
  .description {
    flex: 1;
    padding-left: 10px; /* Adjust as needed */
  }
  .description h2 {
    font-size: 30px;
    font-weight: bold; /* Adjust heading size as needed */
  }
  .description p {
    font-size: 20px; /* Adjust paragraph size as needed */
}
  .social-media {
    margin-top: 0px; /* Adjust margin as needed */
  }
  .social-media a {
    margin: 0 10px; /* Add margin between social media icons */
  }
  .social-media img {
    width: 50px; /* Adjust social media logo size */
    height: auto; /* Maintain aspect ratio */
  }
</style>

<body>

<div class="container">
  <div class="image">
    <img src="assets/theme/images/me.jpg" alt="Image">
  </div>
  <div class="description">
    <h2>Fabian C. Salgado-Roa</h2>
    <p>I’m an evolutionary biologist based at the University of Melbourne. Here, you can explore my research, publications, contact information, and more.</p>
  <div class="social-media">
  <a href="mailto:fcsalgador@gmail.com"><img src="assets/theme/images/mail.png" alt="Mail"></a>
    <a href="https://github.com/fcsalgado"><img src="assets/theme/images/github.png" alt="Github"></a>
    <a href="https://twitter.com/facasaro"><img src="assets/theme/images/twitter.png" alt="Twitter"></a>
    <a href="https://scholar.google.com/citations?user=Oqq-sgcAAAAJ&hl=en&oi=sra"><img src="assets/theme/images/scholar.png" alt="Scholar"></a>
    <!-- Add more social media links and logos as needed -->
</div>
  </div>
</div>

</body>