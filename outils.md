---
layout: page
title: outils
background: grey
---

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
 @media (max-width: 768px) {
  /* Ajoutez un saut de ligne entre "Enquête" et "Dysto-Pique" */
  h2 {
    white-space: pre-line;
  }
}




</style>
</head>

<body>
  <div class="flex-container" style="display: flex; align-items: center;">
    <img src="assets/img/enquete.jpg" alt="horloge" class="photo-enquete" style="flex: 1; margin-right: 60px; max-width: 35%;">
    <div style="flex: 2;">
      <h1 style="text-align: center;">Enquête <br>Dysto Pique</h1>
      <h3 class="section-subheading text-muted" style="text-align: center;">En construction</h3>
      <div class="center-icon">
        <i class="fas fa-person-digging large-icon"></i>
        <div class="text-enquete">
          <p>Plongez dans un futur dystopique fondé sur des problématiques contemporaines. Menez l’enquête afin de forger le récit qui a entraîné cet avenir sombre. Aiguisez votre esprit critique dans un univers où émotions, réflexion et créativité s'entremêlent. Ensemble, envisagez des solutions alternatives pour repenser les choix du présent et leurs répercussions. Découvrez ce voyage dans le temps intriguant !</p>
        </div>
      </div>
    </div>
  </div>
</body>


