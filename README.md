<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Elmac Maciej Lewandowski - Usługi Elektryczne</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0; padding: 0;
    background: #f5f5f5;
    color: #333;
  }
  header {
    background: #005a9c;
    color: white;
    padding: 1em 2em;
    text-align: center;
  }
  nav {
    background: #007acc;
    display: flex;
    justify-content: center;
  }
  nav a {
    color: white;
    text-decoration: none;
    padding: 1em 1.5em;
    display: block;
  }
  nav a:hover {
    background: #005a9c;
  }
  main {
    max-width: 900px;
    margin: 2em auto;
    background: white;
    padding: 2em;
    box-shadow: 0 0 8px rgba(0,0,0,0.1);
  }
  h1, h2 {
    color: #005a9c;
  }
  section {
    margin-bottom: 2em;
  }
  ul {
    padding-left: 1.2em;
  }
  .opinions blockquote {
    background: #eef6fc;
    border-left: 5px solid #007acc;
    margin: 1em 0;
    padding: 1em 1.2em;
    font-style: italic;
  }
  .gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(200px,1fr));
    gap: 1em;
  }
  .gallery img {
    width: 100%;
    border-radius: 4px;
    box-shadow: 0 0 6px rgba(0,0,0,0.1);
  }
  form label {
    display: block;
    margin-bottom: 0.3em;
    font-weight: bold;
  }
  form input, form textarea {
    width: 100%;
    padding: 0.5em;
    margin-bottom: 1em;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-size: 1em;
  }
  form button {
    background: #005a9c;
    color: white;
    border: none;
    padding: 0.7em 1.5em;
    cursor: pointer;
    border-radius: 4px;
    font-size: 1em;
  }
  form button:hover {
    background: #003f6f;
  }
  footer {
    text-align: center;
    padding: 1em;
    background: #eee;
    font-size: 0.9em;
    color: #666;
  }
  @media(max-width:600px) {
    nav {
      flex-direction: column;
      align-items: center;
    }
  }
</style>
</head>
<body>
<header>
  <h1>Elmac Maciej Lewandowski</h1>
  <p>Profesjonalne usługi elektryczne z doświadczeniem</p>
</header>
<nav>
  <a href="#home">Strona główna</a>
  <a href="#services">Zakres usług</a>
  <a href="#opinions">Opinie klientów</a>
  <a href="#gallery">Galeria</a>
  <a href="#contact">Kontakt</a>
</nav>

<main>
  <section id="home">
    <h2>Witamy w Elmac</h2>
    <p>Jesteśmy firmą świadczącą kompleksowe usługi elektryczne na terenie województwa kujawsko-pomorskiego. Posiadamy wieloletnie doświadczenie oraz wszystkie niezbędne uprawnienia do pracy pod napięciem. Gwarantujemy fachowość, terminowość oraz bezpieczeństwo wykonywanych prac.</p>
  </section>

  <section id="services">
    <h2>Zakres usług</h2>
    <ul>
      <li>Montaż instalacji elektrycznych</li>
      <li>Serwis i naprawa instalacji elektrycznych</li>
      <li>Pomiary elektryczne</li>
      <li>Wymiana instalacji elektrycznych</li>
    </ul>
  </section>

  <section id="opinions" class="opinions">
    <h2>Opinie klientów</h2>
    <blockquote>"Profesjonalne podejście i szybka realizacja zlecenia. Polecam serdecznie!" – Jan K.</blockquote>
    <blockquote>"Elmac wykonał u mnie nową instalację – praca wykonana bardzo starannie i terminowo." – Anna M.</blockquote>
    <blockquote>"Bardzo dobry kontakt i fachowa pomoc. Polecam tę firmę każdemu!" – Piotr W.</blockquote>
  </section>

  <section id="gallery" class="gallery">
    <h2>Galeria realizacji</h2>
    <img src="https://via.placeholder.com/400x300?text=Instalacja+1" alt="Instalacja elektryczna 1" />
    <img src="https://via.placeholder.com/400x300?text=Instalacja+2" alt="Instalacja elektryczna 2" />
    <img src="https://via.placeholder.com/400x300?text=Instalacja+3" alt="Instalacja elektryczna 3" />
  </section>

  <section id="contact">
    <h2>Kontakt</h2>
    <p>Masz pytania? Skontaktuj się z nami!</p>
    <p><strong>Adres:</strong> Nieżywięć 22, 87-326 Nieżywięć</p>
    <p><strong>Telefon:</strong> +48 123 456 789</p>
    <p><strong>E-mail:</strong> kontakt@elmac-lewandowski.pl</p>

    <form id="contactForm" action="mailto:kontakt@elmac-lewandowski.pl" method="post" enctype="text/plain">
      <label for="name">Imię i nazwisko:</label>
      <input type="text" id="name" name="name" required />

      <label for="email">Adres e-mail:</label>
      <input type="email" id="email" name="email" required />

      <label for="message">Wiadomość:</label>
      <textarea id="message" name="message" rows="5" required></textarea>

      <button type="submit">Wyślij</button>
    </form>
  </section>
</main>

<footer>
  <p>© 2025 Elmac Maciej Lewandowski | Usługi elektryczne</p>
</footer>
</body>
</html>
