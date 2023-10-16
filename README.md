# Mystique-Puff
<DOCTYPE html>
<html>
<head>
  <title>Accueil - MonSite</title>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#">Accueil</a></li>
        <li><a href="#">Produits</a></li>
        <li><a href="#">À propos</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>
  
  <section class="hero">
    <h1>Bienvenue sur MonSite</h1>
    <p>Découvrez nos produits de qualité.</p>
    <a href="#" class="cta-button">En savoir plus</a>
  </section>
</body>
</html>
<DOCTYPE css>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Styles de base */
body {
  font-family: Arial, sans-serif;
  background-color: #f5f5f5;
}

header {
  background-color: #333;
  color: #fff;
  padding: 10px 0;
}

nav ul {
  list-style: none;
  text-align: center;
}

nav li {
  display: inline;
  margin-right: 20px;
}

nav a {
  text-decoration: none;
  color: #fff;
  font-weight: bold;
}

.hero {
  text-align: center;
  padding: 100px 0;
}

h1 {
  font-size: 2.5em;
  margin-bottom: 20px;
}

p {
  font-size: 1.2em;
  margin-bottom: 30px;
}

.cta-button {
  display: inline-block;
  padding: 10px 20px;
  background-color: #333;
  color: #fff;
  text-decoration: none;
  font-weight: bold;
  border-radius: 5px;
  transition: background-color 0.3s;
}

.cta-button:hover {
  background-color: #444;
}
