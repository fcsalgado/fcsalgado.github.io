---
layout: home
title: 
description: 


background: /assets/theme/images/landscape.png
permalink: /
---

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Image and Description Layout</title>
<style>
  .container {
    display: flex;
    flex-direction: column;
    align-items: center; /* Center align horizontally */
    text-align: center; /* Center align text */
  }
  .image img {
    width: 100%; /* Occupy full width */
    max-width: 300px; /* Set max-width */
    height: auto; /* Maintain aspect ratio */
    border-radius: 50%; /* Make the image round */
  }
  .description {
    padding: 10px; /* Add padding */
  }
  .description h2 {
    font-size: 24px;
    font-weight: bold; /* Adjust heading size as needed */
  }
  .description p {
    font-size: 20px; /* Adjust paragraph size as needed */
  }
  .social-media {
    margin-top: 10px; /* Adjust margin as needed */
  }
  .social-media a {
    display: inline-block; /* Ensure social media icons are displayed inline */
    margin: 0 5px; /* Add margin between social media icons */
  }
  .social-media img {
    width: 30px; /* Adjust social media logo size */
    height: auto; /* Maintain aspect ratio */
  }

  /* Media query for smaller screens */
  @media screen and (max-width: 600px) {
    .container {
      padding: 0 10px; /* Add padding to container */
    }
    .description h2 {
      font-size: 20px; /* Decrease heading size for smaller screens */
    }
    .description p {
      font-size: 14px; /* Decrease paragraph size for smaller screens */
    }
    .social-media img {
      width: 25px; /* Decrease social media logo size for smaller screens */
    }
  }
</style>
<body>

<div class="container">
  <div class="image">
    <img src="assets/theme/images/me.jpg" alt="Image">
  </div>
  <div class="description">
    <h2>Fabian C. Salgado-Roa</h2>
    <p>I’m an evolutionary biologist soon starting as a Stengl-Wyer Scholar at the University of Texas at Austin. Here, you can explore my research, publications, contact information, and more.</p>
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
