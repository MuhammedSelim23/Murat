<!DOCTYPE html>
<html lang="nl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MSM Onderhoud - Steigerhulp</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #005b96;
      color: white;
      padding: 20px 0;
      text-align: center;
      position: relative;
    }

    header img.logo {
      position: absolute;
      top: 10px;
      left: 20px;
      width: 80px;
      height: auto;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
    }

    nav {
      text-align: center;
      margin-top: 10px;
    }

    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
      display: inline-block;
      padding: 8px;
    }

    section {
      max-width: 1000px;
      margin: 40px auto;
      padding: 20px;
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    .hero {
      text-align: center;
    }

    .hero h2 {
      color: #005b96;
    }

    .cta-button {
      background-color: #007acc;
      color: white;
      padding: 12px 24px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-size: 1em;
      text-decoration: none;
      display: inline-block;
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 12px;
    }

    input, textarea {
      padding: 10px;
      font-size: 1em;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    .contact-links {
      margin-top: 20px;
      text-align: center;
    }

    .contact-links a {
      display: inline-block;
      margin: 10px;
      padding: 10px 20px;
      background-color: #28a745;
      color: white;
      border-radius: 5px;
      text-decoration: none;
    }

    .map-container {
      margin-top: 20px;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }

    .gallery img {
      width: 100%;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }

    footer {
      background-color: #003f63;
      color: white;
      text-align: center;
      padding: 15px 0;
      margin-top: 40px;
    }

    .extra-info {
      background-color: #e9f3fb;
      padding: 20px;
      margin-top: 20px;
      border-left: 5px solid #005b96;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 1.8em;
      }

      header img.logo {
        width: 60px;
        top: 10px;
        left: 10px;
      }

      nav a {
        display: block;
        margin: 5px 0;
      }

      section {
        margin: 20px;
        padding: 15px;
      }

      .cta-button {
        width: 100%;
        text-align: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="/mnt/data/MSM klaar.jpg" alt="MSM Logo" class="logo">
    <h1>MSM Onderhoud</h1>
    <nav>
      <a href="#diensten">Diensten</a>
      <a href="#over-ons">Over ons</a>
      <a href="#extra">Waarom MSM?</a>
      <a href="#projecten">Projecten</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Professionele Steigerhulp nodig?</h2>
    <p>Betrouwbaar, veilig en snel geregeld. MSM Onderhoud staat voor je klaar bij elk project.</p>
    <a href="#contact" class="cta-button">Vraag een offerte aan</a>
  </section>

  <section id="diensten">
    <h2>Onze Diensten</h2>
    <ul>
      <li>Op- en afbouw van steigers</li>
      <li>Steigerinspectie en onderhoud</li>
      <li>Veiligheidsadvies voor werken op hoogte</li>
      <li>Ondersteuning bij renovatie en schilderwerk</li>
    </ul>
  </section>

  <section id="over-ons">
    <h2>Over MSM Onderhoud</h2>
    <p>Wij zijn een ervaren team van vakmensen gespecialiseerd in onderhoudswerk en steigerhulp. Met veiligheid en kwaliteit als onze hoogste prioriteit helpen wij bouwbedrijven, schilders en particulieren door heel Nederland.</p>
  </section>

  <section id="extra" class="extra-info">
    <h2>Waarom kiezen voor MSM Onderhoud?</h2>
    <ul>
      <li>+10 jaar ervaring in steigerbouw en onderhoud</li>
      <li>VCA-gecertificeerd en veiligheidsbewust</li>
      <li>Flexibele planning, ook voor spoedklussen</li>
      <li>Uitstekende klanttevredenheid en service</li>
    </ul>
  </section>

  <section id="projecten">
    <h2>Recente Projecten</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/300x200?text=Project+1" alt="Project 1">
      <img src="https://via.placeholder.com/300x200?text=Project+2" alt="Project 2">
      <img src="https://via.placeholder.com/300x200?text=Project+3" alt="Project 3">
    </div>
  </section>

  <section id="contact">
    <h2>Neem contact met ons op</h2>
    <form action="mailto:muhammed.Selim.yldz@gmail.com" method="POST" enctype="text/plain">
      <input type="text" name="naam" placeholder="Je naam" required>
      <input type="email" name="email" placeholder="Je e-mailadres" required>
      <textarea name="bericht" rows="5" placeholder="Je bericht of aanvraag..." required></textarea>
      <button type="submit" class="cta-button">Verstuur</button>
    </form>
    <div class="contact-links">
      <a href="tel:+31612345678">📞 Bel ons</a>
      <a href="https://wa.me/31612345678" target="_blank">💬 WhatsApp</a>
    </div>
    <div class="map-container">
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2466.435785943205!2d5.121420316036217!3d52.09073787973657!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47c66f02172c3a33%3A0xbec71d96cf80b68c!2sUtrecht!5e0!3m2!1snl!2snl!4v1615992838821!5m2!1snl!2snl" width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </div>
  </section>

  <footer>
    &copy; 2025 MSM Onderhoud. Alle rechten voorbehouden.
  </footer>

</body>
</html>
