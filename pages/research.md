---
title: Research
description: As a researcher, I am interested in how phenotypic and genetic diversity change at large geographical scales and the factors influencing the presence of multiple phenotypes within a single population. To answer my research questions, I study multiple animals, but I'm really interested in species with multiple colors.
background: /assets/theme/images/colours.png
permalink: /research/
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Responsive Bio Section</title>
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

    .description p {
      font-size: 18px;
      line-height: 1.6;
      text-align: justify;
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

  <!-- Section 1 -->
  <div class="section">
    <div class="image">
      <img src="https://raw.githubusercontent.com/fcsalgado/fcsalgado.github.io/master/assets/theme/images/fig1.png" alt="Colour polymorphism in spiders">
    </div>
    <div class="description">
      <h2>Colour Polymorphism in Spiders</h2>
      <p>Polymorphic species offer a fantastic model for unraveling how various factors influence phenotypic and genetic diversity over time and across different environments. Coloration is one of the most explored variable phenotypes, and its study has helped us understand how natural selection operates and drives the evolution of traits. However, most of the evidence exploring the association of coloration and environment comes from color polymorphic lineages where color is a sexual signal, creating challenges in interpreting how phenotypic diversity is independently shaped by biotic and abiotic factors. Web-building spiders are a diverse and unexplored group that may provide new insights into processes of local adaptation or spatial variation in selection.</p>
    </div>
  </div>

  <!-- Section 2 -->
  <div class="section">
    <div class="image">
      <img src="https://raw.githubusercontent.com/fcsalgado/fcsalgado.github.io/master/assets/theme/images/ballon.png" alt="Phylogeography and spiders">
    </div>
    <div class="description">
      <h2>Phylogeography</h2>
      <p>Geographical barriers like mountain ranges impede genetic exchange among populations, promoting diversification. The effectiveness of these barriers in limiting gene flow varies between lineages due to each species' dispersal modes and capacities. However, our understanding of how geographic barriers contribute to species diversification comes mostly from well-studied vertebrates and a few arthropods and plants, neglecting organisms unable to fly or walk long distances. I study arthropods, especially spiders, to explore how mountains promote diversification in lineages with distinct dispersal modes, such as long-distance dispersal via ballooning (i.e., using silk to interact with the wind).</p>
    </div>
  </div>

</body>
</html>
