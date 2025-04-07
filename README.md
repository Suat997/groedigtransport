
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
      flex-wrap: wrap;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      padding: 10px 20px;
      display: block;
    }
    .hero {
      background: url('https://source.unsplash.com/1600x600/?truck,transport') no-repeat center center/cover;
      color: white;
      padding: 100px 20px;
      text-align: center;
    }
    .highlight-text {
      color: black;
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

    /* Neuer Abschnitt für Geschäftsführer */
    #geschaeftsfuehrer {
      background-color: #f9f9f9;
      padding: 40px 20px;
      text-align: center;
    }

    #geschaeftsfuehrer h2 {
      color: #003366;
    }

    .geschaeftsfuehrer-info {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 20px;
      margin-top: 20px;
    }

    .geschaeftsfuehrer-foto {
      border-radius: 50%;
      width: 150px;
      height: 150px;
      object-fit: cover;
    }

    .geschaeftsfuehrer-details h3 {
      color: #003366;
    }

    .geschaeftsfuehrer-details p {
      font-size: 16px;
      color: #333;
    }

    /* Mobile-responsive Layout */
    @media (max-width: 768px) {
      .hero {
        padding: 60px 20px;
      }

      nav {
        flex-direction: column;
        gap: 10px;
      }

      .geschaeftsfuehrer-info {
        flex-direction: column;
        text-align: center;
      }

      .geschaeftsfuehrer-foto {
        width: 120px;
        height: 120px;
      }

      section {
        padding: 20px 10px;
      }

      footer {
        padding: 10px 20px;
      }
    }

    @media (max-width: 480px) {
      .hero {
        padding: 50px 20px;
      }

      nav a {
        font-size: 14px;
        padding: 8px 15px;
      }
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
    <a href="#geschaeftsfuehrer">Unser Geschäftsführer</a>
  </nav>

  <div class="hero">
    <h2>Zuverlässiger Transport für jede Strecke</h2>
    <p class="highlight-text">Effizient. Sicher. Pünktlich.</p>
  </div>

  <section id="ueber-uns">
    <h2>Über uns</h2>
    <p>Grödig Transport ist Ihr vertrauensvoller Partner für Logistiklösungen. Mit unserer Erfahrung und modernen Flotte sorgen wir dafür, dass Ihre Waren sicher und termingerecht ihr Ziel erreichen.</p>
  </section>

  <!-- Neuer Abschnitt für den Geschäftsführer -->
  <section id="geschaeftsfuehrer">
    <h2>Unser Geschäftsführer</h2>
    <div class="geschaeftsfuehrer-info">
      <img src="https://via.placeholder.com/150" alt="Foto Geschäftsführer" class="geschaeftsfuehrer-foto">
      <div class="geschaeftsfuehrer-details">
        <h3>Suat Nurcheski</h3>
        <p><strong>Geschäftsführer</strong></p>
        <p>Suat Nurcheski ist der Geschäftsführer von Grödig Transport. Er ist nicht nur ein erfolgreicher Unternehmer, sondern auch ein engagierter Student, der derzeit sein Studium mit Fokus auf Logistik und Wirtschaft fortsetzt. Trotz seines jungen Alters führt er unser Unternehmen mit viel Leidenschaft und Erfahrung.</p>
        <p>Außerdem freut sich Suat darauf, bald zu heiraten, und dieser nächste Schritt in seinem Leben inspiriert ihn, sowohl beruflich als auch privat weiterhin Verantwortung zu übernehmen und die Herausforderungen des Lebens anzunehmen.</p>
      </div>
    </div>
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
    &copy; 2025 Grödig Transport. Alle Rechte vorbehalten.
  </footer>
</body>
</html>
