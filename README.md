# portfolio
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    header {
      background-color: #333;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    header nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
    }
    .section {
      padding: 50px 20px;
      text-align: center;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 20px;
    }
    .project-card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    .project-card img {
      width: 100%;
      border-radius: 10px;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 10px 0;
      position: fixed;
      width: 100%;
      bottom: 0;
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <a href="#">Accueil</a>
      <a href="#">À propos</a>
      <a href="#">Projets</a>
      <a href="#">Contact</a>
    </nav>
  </header>
  
  <div class="section" id="about">
    <h2>À propos de moi</h2>
    <p>Je suis un développeur passionné par la création de solutions numériques. Voici mes projets !</p>
  </div>

  <div class="section" id="projects">
    <h2>Mes Projets</h2>
    <div class="projects">
      <div class="project-card">
        <img src="https://via.placeholder.com/400x300" alt="Projet 1">
        <h3>Projet 1</h3>
        <p>Description du projet.</p>
      </div>
      <div class="project-card">
        <img src="https://via.placeholder.com/400x300" alt="Projet 2">
        <h3>Projet 2</h3>
        <p>Description du projet.</p>
      </div>
    </div>
  </div>

  <footer>
    <p>&copy; 2024 Mon Portfolio</p>
  </footer>
</body>
</html>
