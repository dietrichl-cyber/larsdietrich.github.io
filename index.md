---
layout: default
title: "Home"
---

<style>
  .content-block {
    display: flex;
    gap: 1rem;
    align-items: flex-start;
    flex-wrap: wrap;
    margin-bottom: 1.5rem;
    /* Standard: Mobilansicht */
    flex-direction: column-reverse; /* Bild über Text */
  }

  .content-text {
    flex: 1 1 250px;
    min-width: 250px;
  }

  .content-image {
    flex: 0 0 auto;
  }

  .content-image img {
    border-radius: 12px;
    max-width: 100%;
    height: auto;
  }

  /* Ab Tablet/Desktop: Bild rechts neben Text */
  @media (min-width: 768px) {
    .content-block {
      flex-direction: row; /* Text links, Bild rechts */
    }
  }
</style>

# Welcome

<div class="content-block">
  <div class="content-text">
    <p>
      I am a researcher in botany and science education. My work focuses on treeline research
      as well as ecological education, plant awareness and perception, and the use of
      AI-supported learning environments in higher education teaching.
    </p>
  </div>

  <div class="content-image">
    <img src="/IMG_1922.HEIC"
         alt="Lars Dietrich"
         width="200">
  </div>
</div>

## Research interests

- Molecular reasons for the global treeline phenomenon  
- Ecological literacy and scientific literacy  
- Plant awareness and perception  
- AI-supported learning environments (e.g., chatbots as learning companions)  

## Textbook

<div class="content-block">
  <div class="content-text">
    <p>
      <strong>Schmidt C, Dietrich L (2022).</strong>
      <em>Chemie im Biologiestudium: Von Grund auf verständlich erklärt.</em><br>
      Second Edition. Springer Spektrum.
    </p>

    <p>
      Link:<br>
      <a href="https://link.springer.com/book/10.1007/978-3-662-63416-5">
        https://link.springer.com/book/10.1007/978-3-662-63416-5
      </a>
    </p>
  </div>

  <div class="content-image">
    <img src="/book.jpeg"
         alt="Chemie im Biologiestudium"
         width="200">
  </div>
</div>

## Contact

Email: lars.dietrich@uni-giessen.de  
Institution: Justus Liebig University Gießen  
