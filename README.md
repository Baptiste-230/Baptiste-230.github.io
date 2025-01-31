<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Curriculum Vitae en ligne - Baptiste Dumilly</title>
  <style>
    /* Centre la page et limite la largeur pour un meilleur rendu */
    body {
      max-width: 800px;
      margin: auto;
      font-family: 'Arial', sans-serif;
      color: #2c3e50;
      line-height: 1.6;
    }

    /* Style de l'en-tête */
    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 20px;
      padding-bottom: 10px;
      border-bottom: 2px solid #4a4a4a;
    }

    /* Informations personnelles */
    .personal-info {
      line-height: 1.6;
    }

    /* Mise en forme de l'image */
    .header img {
      border-radius: 50%;
      width: 120px;
      height: 120px;
      object-fit: cover;
    }

    /* Titre pour le nom */
    .name {
      font-size: 2em;
      font-weight: bold;
      color: #333;
    }

    /* Contact aligné à droite */
    .contact-info {
      text-align: right;
    }

    /* Section titles */
    h2 {
      color: #2c3e50;
      margin-top: 40px;
    }

    /* Liens avec icônes */
    .social-icons img {
      width: 20px;
      height: 20px;
      vertical-align: middle;
      margin-right: 5px;
    }

    /* Style des listes */
    ul {
      list-style-type: square;
      padding-left: 20px;
    }

    /* Ligne de séparation personnalisée */
    hr {
      border: none;
      border-top: 1px solid #d1d1d1;
      margin: 30px 0;
    }

    /* Pied de page */
    footer {
      text-align: center;
      margin-top: 50px;
      font-size: 0.9em;
      color: #7f8c8d;
    }

    /* Bouton de téléchargement */
    .download-cv {
      display: block;
      text-align: center;
      margin: 20px 0;
    }

    .download-cv a {
      background-color: #3498db;
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
    }

    .download-cv a:hover {
      background-color: #2980b9;
    }
  </style>
</head>
<body>
  <div class="header">
    <div class="personal-info">
      <div class="name">DUMILLY Baptiste</div>
      <p><strong>Téléphone :</strong> +33 7 68 63 71 23</p>
      <p><strong>Email :</strong> <a href="mailto:baptistedumilly@gmail.com">baptistedumilly@gmail.com</a></p>
      <div class="social-icons">
        <a href="https://www.linkedin.com/in/baptiste-d-8b1290290/" target="_blank">
          <img src="linkedin-icon.png" alt="LinkedIn">LinkedIn
        </a>
        <br>
        <a href="https://github.com/Baptiste-230" target="_blank">
          <img src="github-icon.png" alt="GitHub">GitHub
        </a>
      </div>
    </div>
    <div class="contact-info">
      <img src="photo.jpg" alt="Photo de profil">
    </div>
  </div>

  <hr>

  <h2>Qui suis-je ?</h2>
  <p>Je m’appelle Baptiste, étudiant de 19 ans, actuellement en deuxième année de BUT informatique, parcours « déploiement d’applications communicantes et sécurisées » à l’IUT de Calais. Passionné par l’informatique depuis mes cours de NSI au lycée, j’ai développé une affinité particulière pour les réseaux et la cybersécurité.</p>
  <p>En dehors de mes études, je joue du piano et pratique le dessin en autodidacte. J’apprécie également la lecture (romans et mangas) et les jeux en coopération en ligne. J’aime aussi aider mes amis sur leurs projets de code et créer des petits programmes pour m’amuser.</p>
  <p>Je suis une personne motivée, autonome et curieuse, toujours prête à apprendre et à aider les autres.</p>

  <h2>🎓 Formation</h2>
  <p><strong>Lycée Sophie Berthelot</strong><br>
  <em>Baccalauréat Scientifique, Mention Assez Bien</em><br>
  Obtention : 2022 | Calais, France</p>

  <p><strong>Institut Universitaire de Technologie (IUT) de Calais</strong><br>
  <em>Bachelor Universitaire de Technologie (BUT) en Informatique</em><br>
  En cours depuis 2022 | Calais, France</p>
  <ul>
    <li>Modules clés : Programmation, Réseaux, Base de données, Développement web.</li>
    <li>Projets pratiques réalisés, dont des applications web et scripts réseau.</li>
  </ul>

  <hr>

  <h2>💼 Expérience professionnelle</h2>
  <p><strong>Nom de l'Entreprise</strong><br>
  <em>Poste occupé</em><br>
  Dates d’emploi | Ville, Pays</p>
  <ul>
    <li>Résumé des tâches principales et responsabilités.</li>
    <li>Exemple de réalisation ou résultat mesurable.</li>
    <li>Utilisation d’outils/technologies spécifiques.</li>
  </ul>

  <p><strong>Nom de l'Entreprise</strong><br>
  <em>Poste occupé</em><br>
  Dates d’emploi | Ville, Pays</p>
  <ul>
    <li>Description des tâches et réalisations clés.</li>
    <li>Collaboration avec une équipe ou des départements spécifiques.</li>
    <li>Résultat notable ou impact majeur pour l’entreprise.</li>
  </ul>

  <hr>

  <h2>🛠 Compétences</h2>
  <ul>
    <li><strong>Langages de programmation :</strong> Python, JavaScript, C++</li>
    <li><strong>Outils & Technologies :</strong> Git, Docker, Kubernetes, AWS</li>
    <li><strong>Langues :</strong> Français (natif), Anglais (courant), Espagnol (notions de base)</li>
  </ul>

  <hr>

  <h2>🏆 Projets</h2>
  <h3>Application de gestion des tâches</h3>
  <p>Application web permettant de créer, modifier et suivre des tâches personnelles.</p>
  <ul>
    <li>Technologies utilisées : Python, Flask, PostgreSQL</li>
    <li>Optimisation des requêtes pour une réponse rapide</li>
  </ul>

  <h3>Plateforme de chat en temps réel</h3>
  <p>Application web permettant aux utilisateurs de discuter en temps réel.</p>
  <ul>
    <li>Technologies utilisées : HTML, CSS, JavaScript, Socket.io</li>
    <li>Gestion efficace des connexions utilisateur</li>
  </ul>
