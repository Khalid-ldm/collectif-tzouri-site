<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Collectif Tzouri</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f8f8f8; color: #333; }
    header { background: #000; color: white; padding: 2rem 1rem; text-align: center; }
    header img.logo { max-width: 100px; display: block; margin: 0 auto 1rem; }
    nav { background: #333; padding: 1rem; text-align: center; }
    nav a { color: white; margin: 0 1rem; text-decoration: none; font-weight: bold; }
    section { padding: 2rem; max-width: 900px; margin: auto; }
    footer { background: #000; color: white; text-align: center; padding: 1rem; }
    .gallery { display: flex; flex-wrap: wrap; justify-content: center; gap: 1rem; }
    .gallery img { width: 100%; max-width: 300px; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
    .contact-form input, .contact-form textarea { width: 100%; padding: 0.5rem; margin-bottom: 1rem; border-radius: 4px; border: 1px solid #ccc; }
    .contact-form button { padding: 0.5rem 1rem; background: #333; color: white; border: none; border-radius: 4px; cursor: pointer; }
  </style>
</head>
<body>
  <header>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ac/No_image_available.svg/200px-No_image_available.svg.png" alt="Collectif Tzouri Logo" class="logo">
    <h1>Collectif Tzouri</h1>
    <p>Culture | Art | Community - Oujda, Morocco</p>
  </header>
  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Us</h2>
    <p>Collectif Tzouri is a nonprofit artistic and cultural collective based in Oujda, Morocco. Founded in 2016, we promote creativity, community, and expression through events, festivals, and murals. "Tzouri" means "the beautiful" in Amazigh.</p>
  </section>

  <section id="projects">
    <h2>Our Projects</h2>
    <ul>
      <li><strong>Festival Gaada:</strong> Celebrating urban arts in Oujda.</li>
      <li><strong>Festival Kharbachat:</strong> A creative explosion in rural communities.</li>
      <li><strong>@lgana_space:</strong> A co-working hub for artists and creatives.</li>
    </ul>
  </section>

  <section id="gallery">
    <h2>Gallery</h2>
    <div class="gallery">
      <img src="https://barbarapicci.files.wordpress.com/2023/05/simo-tara-oujda-2023.jpg" alt="Mural by Simo Tara in Oujda">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fc/Street_art_festival_2023.jpg/640px-Street_art_festival_2023.jpg" alt="Street art festival">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5d/Moroccan_street_artist.jpg/640px-Moroccan_street_artist.jpg" alt="Artist at work">
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: collectif.tzouri@gmail.com</p>
    <p>Phone: +212 677-204763</p>
    <p>Follow us on <a href="https://www.instagram.com/collectif_tzouri/" target="_blank">Instagram</a></p>
    <form class="contact-form">
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="4" placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Collectif Tzouri. All rights reserved.</p>
  </footer>
</body>
</html>
