<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Grödig Transport</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f5f5f5;
      color: #333;
    }
    header {
      background-color: #003366;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #004080;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('https://source.unsplash.com/1600x600/?truck,transport') no-repeat center center/cover;
      color: white;
      padding: 100px 20px;
      text-align: center;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #003366;
    }
    .leistungen ul {
      list-style: none;
      padding: 0;
    }
    .leistungen li {
      background: #e0e0e0;
      margin: 10px 0;
      padding: 10px;
      border-left: 5px solid #003366;
    }
    footer {
      background-color: #003366;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Grödig Transport</h1>
    <p>Wir bringen Ihre Ware sicher von A bis Z.</p>
  </header>
  <nav>
    <a href="#ueber-uns">Über uns</a>
    <a href="#leistungen">Leistungen</a>
    <a href="#kontakt">Kontakt</a>
  </nav>

  <div class="hero">
    <h2>Zuverlässiger Transport für jede Strecke</h2>
    <p>Effizient. Sicher. Pünktlich.</p>
  </div>

  <section id="ueber-uns">
    <h2>Über uns</h2>
    <p>Grödig Transport ist Ihr vertrauensvoller Partner für Logistiklösungen. Mit unserer Erfahrung und modernen Flotte sorgen wir dafür, dass Ihre Waren sicher und termingerecht ihr Ziel erreichen.</p>
  </section>

  <section id="leistungen" class="leistungen">
    <h2>Unsere Leistungen</h2>
    <ul>
      <li>Waren- und Frachttransporte national & international</li>
      <li>Express- und Sonderlieferungen</li>
      <li>Zuverlässige Lager- und Logistikdienste</li>
    </ul>
  </section>

  <section id="kontakt">
    <h2>Kontakt</h2>
    <p>Adresse: Musterstraße 1, 5082 Grödig</p>
    <p>Telefon: +43 123 456789</p>
    <p>Email: kontakt@groedig-transport.at</p>
  </section>

  <footer>
    &copy; 2024 Grödig Transport. Alle Rechte vorbehalten.
  </footer>
</body>
</html>
