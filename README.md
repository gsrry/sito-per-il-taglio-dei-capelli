# sito-per-il-taglio-dei-capelli
<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>OneHairstyle</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #fff7f7, #ffe6f0);
      color: #333;
    }

    header {
      background: linear-gradient(135deg, #f49ac2, #fbb1d1);
      padding: 40px 20px;
      text-align: center;
      color: white;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    header h1 {
      font-size: 3.5em;
      margin: 0;
      letter-spacing: 2px;
    }

    header p {
      font-size: 1.3em;
      margin-top: 10px;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      text-align: center;
      font-size: 2.2em;
      margin-bottom: 40px;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 30px;
    }

    .service-card {
      background: white;
      padding: 25px;
      border-radius: 20px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
    }

    .service-card:hover {
      transform: translateY(-5px);
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 20px;
      background: white;
      padding: 30px;
      border-radius: 16px;
      box-shadow: 0 6px 15px rgba(0,0,0,0.1);
      max-width: 600px;
      margin: auto;
    }

    input, textarea, button {
      padding: 12px;
      border-radius: 10px;
      border: 1px solid #ccc;
      font-size: 1em;
    }

    button {
      background: linear-gradient(to right, #f49ac2, #fbb1d1);
      color: white;
      border: none;
      font-weight: bold;
      transition: background 0.3s ease;
    }

    button:hover {
      background: #e088b2;
    }

    footer {
      background: #f49ac2;
      color: white;
      text-align: center;
      padding: 30px;
      font-size: 0.95em;
    }

    a {
      color: white;
      text-decoration: none;
      margin: 0 10px;
      font-weight: bold;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>OneHairstyle</h1>
    <p>La tua bellezza, il nostro stile ✨</p>
  </header>

  <section>
    <h2>I nostri servizi</h2>
    <div class="services">
      <div class="service-card">
        <h3>Taglio donna</h3>
        <p>Tagli moderni, classici e su misura per te.</p>
      </div>
      <div class="service-card">
        <h3>Colore & Meches</h3>
        <p>Dai luce ai tuoi capelli con i nostri colori professionali.</p>
      </div>
      <div class="service-card">
        <h3>Piega</h3>
        <p>Per ogni occasione: elegante, casual o super glamour.</p>
      </div>
      <div class="service-card">
        <h3>Trattamenti</h3>
        <p>Ristrutturazione, anticrespo, keratina e altro ancora.</p>
      </div>
    </div>
  </section>

  <section>
    <h2>Prenota un appuntamento</h2>
    <form>
      <input type="text" placeholder="Nome e Cognome" required>
      <input type="tel" placeholder="Numero di telefono" required>
      <input type="date" required>
      <textarea rows="4" placeholder="Scrivi il servizio desiderato..." required></textarea>
      <button type="submit">Prenota</button>
    </form>
  </section>

  <section>
    <h2>Contatti</h2>
    <p style="text-align: center; font-size: 1.1em;">
      📞 Tel: 333-1234567<br>
      📍 Via dei Capelli 12, Mantova<br>
      📧 Email: info@onehairstyle.it
    </p>
  </section>

  <footer>
    Seguici su:
    <a href="#">Instagram</a>
    <a href="#">Facebook</a>
    <a href="#">TikTok</a>
    <br><br>
    &copy; 2025 OneHairstyle - Tutti i diritti riservati
  </footer>
</body>
</html>
