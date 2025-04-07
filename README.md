
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
    .hero h2 {
      color: #003366;
      font-size: 2.5em;
    }
    .hero p {
      color: black;
      font-size: 1.5em;
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

    /* Sprachauswahl oben rechts */
    .lang-select {
      position: absolute;
      top: 10px;
      right: 20px;
      z-index: 1000;
    }
    .lang-select button {
      padding: 8px 16px;
      background-color: #004080;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .lang-select button:hover {
      background-color: #003366;
    }

    .businessman-photo {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      margin-top: 20px;
    }

    /* Mobile Anpassung */
    @media (max-width:
