---
layout: page
title: outils
background: grey
---

<html>
<head>
  <script src="https://kit.fontawesome.com/ab10f6b37e.js" crossorigin="anonymous"></script>
  <style>
    /* Centrer l'icône horizontalement et verticalement */
    .center-icon {
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      color: grey; /* Couleur grise pour l'icône */
    }
    /* Ajuster la largeur de la photo */
    .photo-enquete {
      max-width: 70%; /* Ajustez la largeur selon vos besoins */
      margin-bottom: 20px;
    }
    /* Augmenter la taille de l'icône */
    .large-icon {
      font-size: 3rem; /* Ajustez la taille selon vos besoins */
    }
    /* Justifier le texte et le rendre noir */
    .text-enquete {
      text-align: justify;
      color: black; /* Couleur noire pour le texte */
    }
    /* Media query pour les écrans plus petits (téléphone) */
    @media (max-width: 768px) {
      .flex-container {
        flex-direction: column-reverse;
        align-items: center;
      }
      /* Ajuster la largeur de la photo pour les écrans plus petits */
      .photo-enquete {
        display: none;
      }
      .text-enquete {
        text-align: left; /* Aligner le texte à gauche */
      }
    }
  
  </style>
</head>
<body>
  <div class="flex-container" style="display: flex; align-items: center;">
    <img src="assets/img/enquete.jpg" alt="horloge" class="photo-enquete" style="flex: 1; margin-right: 60px; max-width: 35%; margin-top: 100px">
    <div style="flex: 2;">
      <h1 style="text-align: center;">Enquêtes</h1>
      <h3 class="section-subheading text-muted" style="text-align: center;">En construction</h3>
      <div class="center-icon">
        <i class="fas fa-person-digging large-icon"></i>
      <h2 style="text-align: center; color: black"><br>Dysto Pique</h2>
      <h5 class="section-subheading text-muted" style="text-align: center;">15 ans et +</h5>
      <div class="text-enquete">
        <p>Plongez dans un futur dystopique fondé sur des problématiques contemporaines. Menez l’enquête afin de forger le récit qui a entraîné cet avenir sombre. Aiguisez votre esprit critique dans un univers où émotions, réflexion et créativité s'entremêlent. Ensemble, envisagez des solutions alternatives pour repenser les choix du présent et leurs répercussions. Découvrez ce voyage dans le temps intriguant !</p>
      </div>
       <div>
      <h2 style="text-align: center; color: black">En quête d'empathie</h2>
      <h5 class="section-subheading text-muted" style="text-align: center;">De 7 à 14 ans</h5>
      <div class="text-enquete">
        <p>Ce jeu d’enquête met en lumière un cas de harcèlement basé sur des scénarios de la vie scolaire. Les élèves démêlent les fils en naviguant à travers la subjectivité des points de vue des protagonistes, ils résolvent des énigmes sociales et s'entraînent à l’auto-défense verbale. C’est un outil pédagogique complet pour prévenir les mécaniques de rejet et encourager la construction de relations sociales saines et épanouissantes en renforçant l'estime de soi et en développant l'empathie.</p>
      </div>
    </div>
  </div>


