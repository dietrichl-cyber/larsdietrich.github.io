---
layout: default
title: "Home"
---

<style>
  /* Layout für Bild+Text-Blöcke */
  .content-block {
    display: flex;
    gap: 1rem;
    align-items: flex-start;
    flex-wrap: wrap;

    /* Standard = Handy */
    flex-direction: column-reverse;
    margin: 0; /* Eigener Block bekommt erstmal KEIN margin-bottom */
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

  /* Weniger Abstand NACH den Bild-Text-Blöcken zur nächsten h2 */
  section .content-block + h2 {
    margin-top: 0.8rem !important;
  }

  /* Generell: h2 im Inhalt enger setzen */
  section h2 {
    margin-top: 1.2rem !important;
    margin-bottom: 0.4rem !important;
  }

  /* Abstände der Texte/Listen verkleinern */
  section p {
    margin-top: 0;
    margin-bottom: 0.5rem;
  }

  section ul {
    margin-top: 0;
    margin-bottom: 0.6rem;
  }

  /* In den Content-Blöcken: letzter Absatz nicht noch extra Abstand nach unten */
  .content-block .content-text p:last-child {
    margin-bottom: 0.2rem !important;
  }

  /* Handy: Bild über Text, geringer Abstand unter dem Bild (Layout-Override mit !important) */
  @media (max-width: 700px) {
    section .content-image img {
      margin: 0 auto 0.4rem auto !important; /* statt 1rem aus deinem Layout */
      display: block;
      max-width: 70%; /* gern ändern auf 100%, wenn du magst */
    }
  }

  /* Ab Tablet/Desktop: Bild rechts neben Text, moderater Block-Abstand */
  @media (min-width: 701px) {
    .content-block {
      flex-direction: row;      /* Text links, Bild rechts */
      margin-bottom: 0.8rem;    /* etwas Luft zwischen Block und nächstem Inhalt */
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
      <em>Chemie im Biologiestudium: Von Grund auf verständlich erklärt.</em> Second Edition. Springer Spektrum.
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
