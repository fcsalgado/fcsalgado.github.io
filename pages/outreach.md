---
title: Outreach
description: 
background: /assets/theme/images/colours.png
permalink: /outreach/
---

<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Outreach</title>
  <style>
    .section {
      display: flex;
      flex-direction: row;
      flex-wrap: wrap;
      align-items: flex-start;
      margin: 20px auto;
      max-width: 1000px;
      gap: 20px;
    }

    .image {
      flex: 1 1 300px;
      max-width: 400px;
    }

    .image img {
      width: 100%;
      height: auto;
      display: block;
      border-radius: 10px;
    }

    .description {
      flex: 2 1 400px;
    }

    .description h2 {
      font-size: 28px;
      margin-bottom: 10px;
    }

    .description h3 {
      font-size: 22px;
      margin-top: 20px;
    }

    .description p {
      font-size: 18px;
      line-height: 1.6;
      text-align: justify;
    }

    .subsection {
      margin-top: 20px;
      padding-left: 10px;
      border-left: 3px solid #ccc;
    }

    @media (max-width: 768px) {
      .section {
        flex-direction: column;
        align-items: center;
        text-align: center;
      }

      .description p {
        text-align: left;
      }
    }
  </style>
</head>

<body>

  <!-- Section 1: COLEVOL -->
  <div class="section">
    <div class="image">
      <img src="https://raw.githubusercontent.com/fcsalgado/fcsalgado.github.io/master/assets/theme/images/colevol.png" alt="Colombian Society of Evolutionary Biology (COLEVOL)">
    </div>
    <div class="description">
      <h2>Colombian Society of Evolutionary Biology (COLEVOL)</h2>
      <p>As undergraduate students at a regional public university in Colombia, my peers and I formed a group dedicated to scientific communication. We met at the main library in our town, creating opportunities for people—especially high school students—to learn about the causes and consequences of biodiversity through public events such as Darwin Day. Through this group, we contributed to the establishment of the Colombian Society of Evolutionary Biology (COLEVOL), a student-run scientific society whose main goal is to spread and promote evolutionary biology in Colombia. I became a key member of this society, serving on the executive board, editing the scientific communication bulletin for two years, and giving public talks in various venues.</p>
      <p>Download or read all COLEVOL bulletins <a href="https://colevol.github.io/boletin/" target="_blank">here</a>.</p>
    </div>
  </div>

  <!-- Section 2: Music -->
  <section id="music">
    <div class="section">
      <div class="image">
        <img src="https://raw.githubusercontent.com/fcsalgado/fcsalgado.github.io/master/assets/theme/images/timi.jpeg" alt="Music">
      </div>
      <div class="description">
        <h2>Music</h2>
        <p>I'm originally from Ibagué-Tolima, the musical capital of Colombia. Growing up there, I built strong connections through music that continue to influence my life.</p>

        <!-- Subsection 2.1 -->
        <div class="subsection">
          <div class="image">
            <img src="https://raw.githubusercontent.com/fcsalgado/fcsalgado.github.io/master/assets/theme/images/ep.jpg.png" alt="Acoustic EP">
          </div>
          <h3>Es mejor no intentar hacer nada</h3>
          <p>During my Ph.D. in Australia, I recorded some acoustic songs that you can check out <a href="https://www.youtube.com/watch?v=uR458iCBIU4" target="_blank">here</a>.</p>
        </div>

        <!-- Subsection 2.2 -->
        <div class="subsection">
          <h3>Trying to Find Me</h3>
          <div class="image">
            <img src="https://raw.githubusercontent.com/fcsalgado/fcsalgado.github.io/master/assets/theme/images/ttfm.jpeg" alt="Trying to Find Me album cover">
          </div>
          <p>While in Ibagué, I was lucky enough to play music with some of my best friends. They still perform and recently released a new album—<a href="https://open.spotify.com/artist/2WpvZkinRCOkiYnPAniPUg?si=ugimt0OTTRiScpsgyM9jcQ" target="_blank">check them out here</a>.</p>
        </div>

        <!-- Subsection 2.3 -->
        <div class="subsection">
          <h3>More music from Ibagué</h3>
          <div class="section" style="flex-wrap: wrap; gap: 30px;">
            <p>Other friends of mine have amazing bands. Check out their tunes whether you're having a sunny or cloudy day, or if you're feeling sad, happy, or lost.</p>

            <!-- Image 1 -->
            <div class="image" style="max-width: 300px;">
              <img src="https://raw.githubusercontent.com/fcsalgado/fcsalgado.github.io/master/assets/theme/images/insoc.jpeg" alt="Los Insoportables performance">
              <p style="font-size: 16px; text-align: justify; margin-top: 10px;">Los Insoportables play fast tunes that are perfect for when you hate this world. <a href="https://open.spotify.com/artist/7dsOmNX60KbDw1bHSlrpap?si=XJwmmNxvR22CV5dRZ0vVdA" target="_blank">Check them out here</a>.</p>
            </div>

            <!-- Image 2 -->
            <div class="image" style="max-width: 300px;">
              <img src="https://raw.githubusercontent.com/fcsalgado/fcsalgado.github.io/master/assets/theme/images/senseless.jpeg" alt="Senseless recording session">
              <p style="font-size: 16px; text-align: justify; margin-top: 10px;">Senseless plays romantic and sad tunes from the tropical Andes. <a href="https://open.spotify.com/artist/533LrBbxCyB8tjhVtzs9y6?si=Bir5mcrQTlC9iO0xgme66Q" target="_blank">Check them out here</a>.</p>
            </div>

          </div>
        </div>

      </div>
    </div>
  </section>

</body>
</html>
