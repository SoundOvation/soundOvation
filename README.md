## Hi there 👋
<!DOCTYPE html>
<html lang="sk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>soundOvation</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }

    body {
      background: #fafafa;
      color: #1a1a1a;
      line-height: 1.6;
    }

    header {
      padding: 4rem 2rem;
      text-align: center;
      background: #fff;
      border-bottom: 1px solid #eee;
    }

    header h1 {
      font-size: 2.5rem;
      font-weight: 700;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      margin: 1rem 0;
    }

    nav a {
      text-decoration: none;
      color: #555;
      font-weight: 500;
      transition: color 0.2s ease-in-out;
    }

    nav a:hover {
      color: #000;
    }

    section {
      max-width: 800px;
      margin: 4rem auto;
      padding: 0 2rem;
    }

    h2 {
      font-size: 1.8rem;
      margin-bottom: 1rem;
      border-left: 4px solid #000;
      padding-left: 0.5rem;
    }

    .portfolio audio, .portfolio iframe {
      width: 100%;
      margin: 1rem 0;
    }

    form input, form textarea, form button {
      display: block;
      width: 100%;
      margin: 0.5rem 0;
      padding: 0.75rem;
      font-size: 1rem;
    }

    form button {
      background: #000;
      color: #fff;
      border: none;
      cursor: pointer;
    }

    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #888;
    }

    .lang-btn {
      background: #000;
      color: #fff;
      padding: 0.5rem;
      cursor: pointer;
      border: none;
      position: fixed;
      top: 10px;
      right: 10px;
      z-index: 100;
    }

    .hidden {
      display: none;
    }
  </style>
</head>
<body>
  <!-- Language toggle button -->
  <button class="lang-btn" onclick="toggleLanguage()">EN | SK</button>

  <header>
    <h1 id="title-sk">soundOvation</h1>
    <h1 id="title-en" class="hidden">soundOvation</h1>
    <nav>
      <a href="#uvod" class="nav-sk">Úvod</a>
      <a href="#uvod" class="nav-en hidden">Introduction</a>
      <a href="#onas" class="nav-sk">O nás</a>
      <a href="#onas" class="nav-en hidden">About</a>
      <a href="#sluzby" class="nav-sk">Služby</a>
      <a href="#sluzby" class="nav-en hidden">Services</a>
      <a href="#portfolio" class="nav-sk">Portfólio</a>
      <a href="#portfolio" class="nav-en hidden">Portfolio</a>
      <a href="#kontakt" class="nav-sk">Kontakt</a>
      <a href="#kontakt" class="nav-en hidden">Contact</a>
    </nav>
  </header>

  <section id="uvod">
    <h2 id="uvod-sk">Úvod</h2>
    <h2 id="uvod-en" class="hidden">Introduction</h2>
    <p id="intro-sk">Profesionálny zvuk pre váš obraz. Voice-over, mix, sound design — to všetko pod jednou strechou.</p>
    <p id="intro-en" class="hidden">Professional sound for your visuals. Voice-over, mixing, sound design — all under one roof.</p>
  </section>

  <section id="onas">
    <h2 id="onas-sk">O nás</h2>
    <h2 id="onas-en" class="hidden">About</h2>
    <p id="about-sk">Zatiaľ bez textu – pripravujeme.</p>
    <p id="about-en" class="hidden">Content coming soon – stay tuned.</p>
  </section>

  <section id="sluzby">
    <h2 id="sluzby-sk">Služby</h2>
    <h2 id="sluzby-en" class="hidden">Services</h2>
    <ul>
      <li id="service1-sk">Voice-over nahrávky</li>
      <li id="service1-en" class="hidden">Voice-over recordings</li>
      <li id="service2-sk">Mixáž audiovizuálnych diel</li>
      <li id="service2-en" class="hidden">Mixing audiovisual works</li>
      <li id="service3-sk">Sound design</li>
      <li id="service3-en" class="hidden">Sound design</li>
      <li id="service4-sk">Mastering</li>
      <li id="service4-en" class="hidden">Mastering</li>
    </ul>
  </section>

  <section id="portfolio" class="portfolio">
    <h2 id="portfolio-sk">Portfólio</h2>
    <h2 id="portfolio-en" class="hidden">Portfolio</h2>
    <p id="portfolio-desc-sk">Ukážky zvuku:</p>
    <p id="portfolio-desc-en" class="hidden">Audio samples:</p>
    <audio controls src="#">Váš prehliadač nepodporuje prehrávanie audia.</audio>
    <p>Ukážky videa:</p>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Ukážkové video" frameborder="0" allowfullscreen></iframe>
  </section>

  <section id="kontakt">
    <h2 id="kontakt-sk">Kontakt</h2>
    <h2 id="kontakt-en" class="hidden">Contact</h2>
    <form>
      <input type="text" placeholder="Vaše meno" required />
      <input type="email" placeholder="Emailová adresa" required />
      <textarea placeholder="Správa" rows="5" required></textarea>
      <button type="submit">Odoslať</button>
    </form>
  </section>

  <footer>
    <p id="footer-sk">&copy; 2025 soundOvation. Všetky práva vyhradené.</p>
    <p id="footer-en" class="hidden">&copy; 2025 soundOvation. All rights reserved.</p>
  </footer>

  <script>
    function toggleLanguage() {
      // Toggle visibility of elements based on language
      let elementsSk = document.querySelectorAll('.nav-sk, #title-sk, #intro-sk, #onas-sk, #sluzby-sk, #portfolio-sk, #kontakt-sk, #footer-sk');
      let elementsEn = document.querySelectorAll('.nav-en, #title-en, #intro-en, #onas-en, #sluzby-en, #portfolio-en, #kontakt-en, #footer-en');
      
      elementsSk.forEach(el => el.classList.toggle('hidden'));
      elementsEn.forEach(el => el.classList.toggle('hidden'));
    }
  </script>
</body>
</html>

<!--
**SoundOvation/soundOvation** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
