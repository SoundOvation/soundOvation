<!DOCTYPE html>
<html lang="sk">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>soundOvation</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;500;700&display=swap" rel="stylesheet" />
    <style>
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: 'Inter', sans-serif;
      }

      body {
        background: #ffffff;
        color: #1a1a1a;
        line-height: 1.6;
      }

      header {
        padding: 3rem 2rem;
        text-align: center;
        background: linear-gradient(to right, #000000, #434343);
        color: white;
      }

      header h1 {
        font-size: 3rem;
        font-weight: 700;
        letter-spacing: 2px;
      }

      nav {
        display: flex;
        justify-content: center;
        gap: 2rem;
        background: #f7f7f7;
        padding: 1rem;
        box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
      }

      nav a {
        text-decoration: none;
        color: #333;
        font-weight: 500;
        transition: color 0.2s ease-in-out;
      }

      nav a:hover {
        color: #000;
      }

      section {
        max-width: 900px;
        margin: 4rem auto;
        padding: 0 2rem;
        border-left: 4px solid #000;
      }

      h2 {
        font-size: 2rem;
        margin-bottom: 1rem;
      }

      .placeholder {
        height: 150px;
        background: #f0f0f0;
        display: flex;
        align-items: center;
        justify-content: center;
        color: #999;
        font-style: italic;
        border-radius: 0.5rem;
      }

      footer {
        text-align: center;
        padding: 2rem;
        font-size: 0.9rem;
        color: #888;
        background: #f2f2f2;
        margin-top: 3rem;
      }
    </style>
  </head>
  <body>
    <header>
      <h1>soundOvation</h1>
    </header>

    <nav>
      <a href="#uvod">Úvod</a>
      <a href="#onas">O nás</a>
      <a href="#sluzby">Služby</a>
      <a href="#portfolio">Portfólio</a>
      <a href="#kontakt">Kontakt</a>
    </nav>

    <section id="uvod">
      <h2>Úvod</h2>
      <div class="placeholder">Obsah pripravujeme</div>
    </section>

    <section id="onas">
      <h2>O nás</h2>
      <div class="placeholder">Obsah pripravujeme</div>
    </section>

    <section id="sluzby">
      <h2>Služby</h2>
      <div class="placeholder">Obsah pripravujeme</div>
    </section>

    <section id="portfolio">
      <h2>Portfólio</h2>
      <div class="placeholder">Obsah pripravujeme</div>
    </section>

    <section id="kontakt">
      <h2>Kontakt</h2>
      <div class="placeholder">Obsah pripravujeme</div>
    </section>

    <footer>
      &copy; 2025 soundOvation. Všetky práva vyhradené.
    </footer>
  </body>
</html>

