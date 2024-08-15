---
layout: page
title: nous
background: grey
---

<style>

  .force-icon {
    color: #49A695;
  }

  /* Styles pour la section "Nous" */
  .nous-section {
      background-color: grey;
      position: relative;
      background-image: url('assets/img/nous_3.jpg');
      background-size: contain;
      /* Ajuste la taille de l'image pour qu'elle tienne entièrement dans la section tout en maintenant son aspect ratio */
      background-position: center;
      height: 500px;
      text-align: center;
      color: transparent;
      padding: 100px 0;
  }

  .nous-section::before {
      content: "COANIMA,";
      position: center;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-family: "Montserrat";
      /* Utilise la police "autography" */
      color: white;
      font-size: 60px;
      border-radius: 5px;
  }

  .nous-section::after {
      content: "c'est nous";
      position: center;
      top: 50%;
      left: 50%;
      transform: translate(-50%, 50%);
      /* Pour déplacer le texte vers le bas */
      color: rgb(255, 255, 255);
      font-family: "Droid Serif";
      font-style: italic;
      color: white;
      font-size: 60px;
      border-radius: 5px;
  }    

  .logo {
    width: 100%;
    height: auto;
  }

  .equipe {
    margin: 1.5em 0;
    text-align: center;
  }

  .description {
    text-align: justify;
  }

  .photo-equipe {
    float: left;
    margin-right: 1em;
    width: 100px;
    height: 100px;
    height: 100%;
    border-radius: 50%;
  }

  .force-icon {
    display: inline-block;
    text-align: center;
    margin: 0 3em;
  }

  .force-icon span {
    display: block;
  }

  /* Styles pour la version ordinateur */
  .contact-info {
    float: left;
    margin-top: 25px;
    margin-right: 20px;
  }

  .ce-que-j-apporte,
  .mes-forces {
    margin: 3em 0;
    text-align: center;
  }

  .ce-que-j-apporte h5,
  .mes-forces h5 {
     font-size: 1em;
   }

  /* Styles pour la version mobile (écran de moins de 600px de largeur) */
  @media (max-width: 600px) {
    .contact-info {
      float: none;
      margin: 0;
    }
    .description {
      margin-top: 25px;
    }
     .nous-section::before{
      font-size:50px
  }
    .nous-section::after{
      font-size:40px
  }



</style>

<head>
  <script src="https://kit.fontawesome.com/ab10f6b37e.js" crossorigin="anonymous"></script>
</head>

<section class="page-section nous-section">
  <div class="container">
    <div class="row">
      <div class="col-lg-12 text-center">
        <h2 class="section-heading text-uppercase"></h2>
      </div>
    </div>
  </div>
</section>

{% include timeline.html %}

<div class="container">
  <div class="flex-container">
    <div class="flex-item">
      <h1><center>Nom</center></h1>
      <p>
        <strong>COANIMA</strong> c’est l’animation collective, coopérative et notre mode de fonctionnement collégial, tous ces mots en CO qui parlent de l’expérience commune, du partage, de l’enrichissement par le groupe. Et pourquoi animation ? de la racine <strong>anima</strong> qui donne la vie. On se fixe pour objectif dans toutes nos animations donner vie aux discussions, aux débats, aux idées, de créer de l’animation dans le cerveau, utiliser notre esprit critique, de bouger aussi et rendre mobile le corps trop souvent oublié dans l’apprentissage.
      </p>
    </div>
    <div class="flex-item">
      <img src="assets/img/gros-logo.jpg" alt="logo coanima" class="logo">
      <p class="text-center">Retrouvez nos statuts <a href="/statuts">ici</a></p>
    </div>
    <div class="flex-item">
      <h1 class="text-center">Logo</h1>
      <p>
        Ce logo représente un grand C, tel les arcs de cercle de chaises qu’on met en place au début de nos interventions. Les lettres o et a suivent, comme les 3 premières lettres de COANIMA. Cela fait le son [kwa] - "quoi?" -, toutes ces questions que l'on pose et qu’on nous pose lors de nos ateliers. Ces deux lettres liées font comme une esperluette (&) couchée, logotype cher à notre cœur, représentant l’union, le lien, le fil continu. Dans esperluette, il y a ESPÈRE (l’espoir) et LUETTE (impliquée dans la voix et donc la communication).
      </p>
    </div>
  </div>
</div>

<div style="height: 75px;"></div>


<h2>Louna</h2>

<img class="photo-equipe" src="assets/img/team/photo-louna-500x500.jpg" alt="Louna" />

<!-- Informations de contact de Louna -->
<div class="contact-info">
  <i class="fa-solid fa-phone fa-lg"></i> <a href="tel:+33744838371">+33 7 44 83 83 71</a> <br>
  <i class="fa-solid fa-envelope fa-lg"></i> <a href="mailto:louna@coanima.org">louna@coanima.org</a>
</div>

<p class="description">À 17 ans j'accède à mon premier emploi dans l'animation. Ma mission est déjà la lutte contre les discriminations et c'est pour moi une révélation. Cela m'a permis de m'engager concrètement contre les injustices et les inégalités par le biais de l'éducation populaire plutôt qu'en manifestante ou politicienne. L'animation fut pour moi une évidence, et surtout j'adorais ça. Des années plus tard, comme animatrice réseau, j'ai pris beaucoup de plaisir à transmettre mes connaissances, concevoir de nouveaux ateliers, les expérimenter, créer de nouveaux thèmes et interagir avec des publics variés. Pour moi, COANIMA est à la fois la réponse et la question : un espace de création, de coopération, d’empathie, que va-t-on bien pouvoir inventer de chouette dans ce joli cadre ?</p>

<div class="ce-que-j-apporte">
  <h5>Ce que j’apporte au collectif</h5>
  <p class="text-center">La gestion du site et des données, la comptabilité, les notions agile/lean.</p>
</div>

<div class="mes-forces">
  <h5>Mes forces</h5>
    <div class="force-icon">
      <i class="fa-solid fa-sun fa-3x"></i>
      <span>Énergique</span>
    </div>
    <div class="force-icon">
      <i class="fa-regular fa-copyright fa-3x"></i>
      <span>Authenticité</span>
    </div>
    <div class="force-icon">
      <i class="fa-solid fa-lightbulb fa-3x"></i>
      <span>Inventive</span>
    </div>
</div>

<h2>Manon</h2>

  <img src="assets/img/team/photo-manon-500x500.jpg" class="photo-equipe" alt="Manon" />

<!-- Informations de contact de Manon -->
<div class="contact-info">
  <i class="fa-solid fa-phone fa-lg"></i> <a href="tel:+33677889335">+33 6 77 88 93 35</a> <br>
  <i class="fa-solid fa-envelope fa-lg"></i> <a href="mailto:manon@coanima.org">manon@coanima.org</a>
</div>

<p class="description">Amoureuse de l’éducation populaire depuis mon premier emploi dans l’associatif en 2011, je me suis engagée jusqu’alors à la lutte contre les discriminations. En expliquant le mécanisme qui entraîne préjugés et rejet, j’ai trouvé une voie (ma voix), du sens et une mission. Sur ce itineraire je me suis enrichie, peut-être encore plus que les publics si divers que j’ai rencontrés. Aujourd’hui j’aspire à aller plus en profondeur dans la compréhension des comportements humains (paix, émotions, besoins, altruisme, écologie…). Je vois dans COANIMA la liberté que j’ai toujours rêvé d’avoir et la confiance en mes collègues pour avancer plus loin, avec plus de folie aussi et de légèreté.</p>

<div class="ce-que-j-apporte">
  <h5>Ce que j’apporte au collectif</h5>
  <p class="text-center">Un réseau partenarial fort, la communication visuelle, la programmation annuelle et la démarche qualité.</p>
</div>

<div class="mes-forces">
<h5>Mes forces</h5>
  <div class="force-icon">
    <i class="fa-solid fa-heart-pulse fa-3x"></i>
    <span>Sensibilité</span>
  </div>

  <div class="force-icon">
    <i class="fa-regular fa-comments fa-3x"></i>
    <span>Communication</span>
  </div>

  <div class="force-icon">
    <i class="fa-brands fa-hotjar fa-3x"></i>
    <span>Adaptabilité</span>
  </div>
</div>

<h2>Audric</h2>

<img src="assets/img/team/photo-audric-500x500.jpg" class="photo-equipe" alt="Audric" />

<!-- Informations de contact de Audric -->
<div class="contact-info">
  <i class="fa-solid fa-phone fa-lg"></i> <a href="tel:+33783677212">+33 7 44 71 88 72</a> <br>
  <i class="fa-solid fa-envelope fa-lg"></i> <a href="mailto:audric@coanima.org">audric@coanima.org</a>
</div>

<p class="description">La richesse de mon parcours se base sur la diversité de mes expériences. J’ai traversé différents horizons professionnels et eu différents engagements dans la lutte contre les discriminations. Ma passion éclectique pour les sciences m'a conduit à étudier le Génie Mécanique, la Sociologie et la Philosophie. Nourris de ces expériences, muni de mon DEJEPS DPTR, je m'engage maintenant dans COANIMA, où se marient harmonieusement pédagogie, curiosité et créativité. Cet espace offre une toile idéale pour cultiver des idées neuves et grandir par l’intelligence collective tout en collaborant avec une équipe de confiance avec qui je partage mes valeurs.</p>

<div class="ce-que-j-apporte">
  <h5>Ce que j’apporte au collectif</h5>
  <p class="text-center">Toutes les veilles (scientifiques, pédagogiques, politiques, réglementaires…) et l’écriture des dossiers de subvention.</p>
</div>

<div class="mes-forces">
<h5>Mes forces</h5>
  <div class="force-icon">
    <i class="fa-solid fa-users fa-3x"></i>
    <span>Sociabilité</span>
  </div>

  <div class="force-icon">
    <i class="fa-brands fa-searchengin fa-3x"></i>
    <span>Curiosité</span>
  </div>

  <div class="force-icon">
    <i class="fa-solid fa-head-side-virus fa-3x"></i>
    <span>Esprit Critique</span>
  </div>
</div>

{% include about.html %}