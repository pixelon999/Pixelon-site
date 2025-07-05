<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pixelon</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(to bottom, #0f0f2e, #1a1a3d);
      color: #fff;
    }
    header {
      padding: 20px;
      text-align: center;
      background-color: #1e1e3f;
    }
    header h1 {
      margin: 0;
      font-size: 2em;
      color: #61dafb;
    }
    nav {
      display: flex;
      justify-content: space-around;
      background-color: #292952;
      padding: 10px 0;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      font-size: 1em;
    }
    section {
      padding: 20px;
    }
    .hero {
      text-align: center;
    }
    .hero img {
      width: 100%;
      max-width: 300px;
    }
    .games {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    .game-card {
      background-color: #2c2c4f;
      padding: 15px;
      border-radius: 10px;
    }
    .contact {
      background-color: #1e1e3f;
      padding: 20px;
      text-align: center;
    }
    .contact input, .contact textarea {
      width: 90%;
      padding: 10px;
      margin: 10px 0;
      border: none;
      border-radius: 5px;
    }
    .contact button {
      background-color: #61dafb;
      border: none;
      padding: 10px 20px;
      color: #000;
      border-radius: 5px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>Pixelon</h1>
    <p>Crafting the Future of Games</p>
  </header>  <nav>
    <a href="#home">Home</a>
    <a href="#games">Games</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>  <section class="hero" id="home">
    <img src="https://via.placeholder.com/300x150?text=Pixelon+Logo" alt="Pixelon Logo" />
    <h2>Welcome to Pixelon</h2>
    <p>Innovative, immersive, and unforgettable game experiences.</p>
  </section>  <section id="games">
    <h2>Our Games</h2>
    <div class="games">
      <div class="game-card">
        <h3>Game Title One</h3>
        <p>Short description about the game goes here.</p>
      </div>
      <div class="game-card">
        <h3>Game Title Two</h3>
        <p>Another cool game description here.</p>
      </div>
    </div>
  </section>  <section id="about">
    <h2>About Pixelon</h2>
    <p>Pixelon is a creative game studio pushing the boundaries of play, art, and technology. Founded by passionate developers and artists, we aim to create worlds you can lose yourself in.</p>
  </section>  <section class="contact" id="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="4" placeholder="Your Message"></textarea>
      <button type="submit">Send</button>
    </form>
  </section>
</body>
</html>
