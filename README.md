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
    .lang-select {
      text-align: right;
      margin: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1 id="header-title">Grödig Transport</h1>
    <p id="header-description">Wir bringen Ihre Ware sicher von A bis Z.</p>
  </header>
  <nav>
    <a href="#ueber-uns" id="nav-about">Über uns</a>
    <a href="#leistungen" id="nav-services">Leistungen</a>
    <a href="#kontakt" id="nav-contact">Kontakt</a>
  </nav>

  <div class="hero">
    <h2 id="hero-title">Zuverlässiger Transport für jede Strecke</h2>
    <p id="hero-subtitle">Effizient. Sicher. Pünktlich.</p>
  </div>

  <section id="ueber-uns">
    <h2 id="about-title">Über uns</h2>
    <p id="about-description">Grödig Transport ist Ihr vertrauensvoller Partner für Logistiklösungen. Mit unserer Erfahrung und modernen Flotte sorgen wir dafür, dass Ihre Waren sicher und termingerecht ihr Ziel erreichen.</p>
  </section>

  <section id="leistungen" class="leistungen">
    <h2 id="services-title">Unsere Leistungen</h2>
    <ul>
      <li id="service1">Waren- und Frachttransporte national & international</li>
      <li id="service2">Express- und Sonderlieferungen</li>
      <li id="service3">Zuverlässige Lager- und Logistikdienste</li>
    </ul>
  </section>

  <section id="kontakt">
    <h2 id="contact-title">Kontakt</h2>
    <p id="contact-address">Adresse: Musterstraße 1, 5082 Grödig</p>
    <p id="contact-phone">Telefon: +43 123 456789</p>
    <p id="contact-email">Email: kontakt@groedig-transport.at</p>
  </section>

  <footer>
    &copy; 2024 Grödig Transport. Alle Rechte vorbehalten.
  </footer>

  <div class="lang-select">
    <button onclick="changeLanguage('de')">Deutsch</button>
    <button onclick="changeLanguage('it')">Italiano</button>
  </div>

  <script>
    function changeLanguage(language) {
      const texts = {
        de: {
          "header-title": "Grödig Transport",
          "header-description": "Wir bringen Ihre Ware sicher von A bis Z.",
          "nav-about": "Über uns",
          "nav-services": "Leistungen",
          "nav-contact": "Kontakt",
          "hero-title": "Zuverlässiger Transport für jede Strecke",
          "hero-subtitle": "Effizient. Sicher. Pünktlich.",
          "about-title": "Über uns",
          "about-description": "Grödig Transport ist Ihr vertrauensvoller Partner für Logistiklösungen. Mit unserer Erfahrung und modernen Flotte sorgen wir dafür, dass Ihre Waren sicher und termingerecht ihr Ziel erreichen.",
          "services-title": "Unsere Leistungen",
          "service1": "Waren- und Frachttransporte national & international",
          "service2": "Express- und Sonderlieferungen",
          "service3": "Zuverlässige Lager- und Logistikdienste",
          "contact-title": "Kontakt",
          "contact-address": "Adresse: Buchbichl 2, 5082 Grödig",
          "contact-phone": "Telefon: +43 123 456789",
          "contact-email": "Email: kontakt@groedig-transport.at"
        },
        it: {
          "header-title": "Grödig Transport",
          "header-description": "Trasportiamo le tue merci in sicurezza da A a Z.",
          "nav-about": "Chi siamo",
          "nav-services": "Servizi",
          "nav-contact": "Contatti",
          "hero-title": "Trasporto affidabile per ogni percorso",
          "hero-subtitle": "Efficiente. Sicuro. Puntuale.",
          "about-title": "Chi siamo",
          "about-description": "Grödig Transport è il tuo partner fidato per soluzioni logistiche. Con la nostra esperienza e la nostra flotta moderna, garantiamo che le tue merci arrivino in sicurezza e puntualmente a destinazione.",
          "services-title": "I nostri Servizi",
          "service1": "Trasporti di merci a livello nazionale e internazionale",
          "service2": "Consegne espresse e speciali",
          "service3": "Servizi affidabili di magazzinaggio e logistica",
          "contact-title": "Contatti",
          "contact-address": "Indirizzo: Buchbichl 2, 5082 Grödig",
          "contact-phone": "Telefono: +43 123 456789",
          "contact-email": "Email: contatti@groedig-transport.it"
        }
      };

      const currentTexts = texts[language];
      
      Object.keys(currentTexts).forEach(key => {
        document.getElementById(key).textContent = currentTexts[key];
      });
    }
  </script>
</body>
</html>
