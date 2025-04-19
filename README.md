<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600;800&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg-color: #0a0a0a;
      --text-color: #d1d1d1;
      --accent-color: #00bcd4;
    }
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Inter', sans-serif;
      background-color: var(--bg-color);
      color: var(--text-color);
      line-height: 1.6;
      overflow-x: hidden;
    }
    header, section, footer {
      padding: 3rem 2rem;
      animation: fadeIn 1.5s ease-in;
    }
    h1, h2, h3 {
      font-family: 'Orbitron', sans-serif;
      color: var(--accent-color);
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      margin-bottom: 3rem;
      font-weight: 600;
    }
    nav a {
      color: var(--accent-color);
      text-decoration: none;
      transition: transform 0.3s;
    }
    nav a:hover {
      transform: scale(1.1);
    }
    .hero {
      background: url('https://wallpaperaccess.com/full/2203127.jpg') center/cover no-repeat;
      text-align: center;
      padding: 10rem 2rem;
      color: #fff;
    }
    .hero h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.25rem;
    }
    .section {
      margin: 4rem 0;
    }
    .btn {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.75rem 1.5rem;
      background-color: var(--accent-color);
      color: #000;
      border: none;
      border-radius: 20px;
      cursor: pointer;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.3s ease;
    }
    .btn:hover {
      background-color: #008c9e;
    }
    footer {
      background: #111;
      color: #999;
      padding: 2rem;
      text-align: center;
      border-radius: 50% 50% 0 0 / 20% 20% 0 0;
      margin-top: 5rem;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes float {
      0% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
      100% { transform: translateY(0); }
    }
    .floating {
      animation: float 4s ease-in-out infinite;
    }
  </style>
</head>
<body>
  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>  <section class="hero floating">
    <h1>Hi, I'm Aminul Haque Shourob</h1>
    <p>Full Stack Developer | Dream Architect | Code Inceptionist</p>
  </section>  <section id="about" class="section">
    <h2>About Me</h2>
    <p>With 4 years of experience building immersive full stack applications, I craft dreams within dreams—using React, Node.js, and cutting-edge tech to deliver next-gen web experiences.</p>
  </section>  <section id="projects" class="section">
    <h2>Projects</h2>
    <ul>
      <li><strong>DreamVerse:</strong> A portfolio site inspired by the layered beauty of Inception.</li>
      <li><strong>InceptCommerce:</strong> A sleek eCommerce solution with a noir twist.</li>
    </ul>
  </section>  <section id="contact" class="section">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:aminul@example.com">aminul@example.com</a></p>
    <p>GitHub: <a href="https://github.com/aminulshourob" target="_blank">@aminulshourob</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/aminulshourob" target="_blank">aminulshourob</a></p>
  </section>  <footer>
    &copy; 2025 Aminul Haque Shourob — "You're waiting for a dream. A coded dream."
  </footer>
</body>
</html>
