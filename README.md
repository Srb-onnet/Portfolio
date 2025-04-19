/* The code needs to be separated into multiple HTML files for a multi-page site. Here's a breakdown: */

/* index.html */

<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Home</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600;800&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="bg-art">
    <section class="hero">
      <img src="https://cdn-icons-png.flaticon.com/512/3017/3017511.png" alt="space icon" class="illustration">
      <h2>Hi, I'm Aminul</h2>
      <p>A full stack web developer with 4 years of experience, passionate about creating immersive web experiences that feel like a dream within a dream.</p>
      <a href="about.html" class="btn">Explore More</a>
    </section>
  </div>
  <footer>
    &copy; 2025 Aminul Haque Shourob. "You're waiting for a dream. A coded dream."
  </footer>
</body>
</html>/* about.html */

<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>About</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600;800&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <section class="about">
    <h3>About Me</h3>
    <p>
      I'm a digital architect inspired by the multilayered storytelling of <em>Inception</em>. I craft digital dreams with React, Node.js, and more.
    </p>
    <a href="projects.html" class="btn">See Projects</a>
  </section>
  <footer>
    &copy; 2025 Aminul Haque Shourob.
  </footer>
</body>
</html>/* projects.html */

<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Projects</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600;800&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <section class="projects">
    <h3>Featured Projects</h3>
    <div class="project-card">
      <h4>Dreamverse</h4>
      <p>A cinematic portfolio inspired by Inception's dream levels. React + GSAP.</p>
    </div>
    <div class="project-card">
      <h4>InceptCommerce</h4>
      <p>Noir-themed eCommerce built using Node and MongoDB.</p>
    </div>
    <a href="contact.html" class="btn">Contact Me</a>
  </section>
  <footer>
    &copy; 2025 Aminul Haque Shourob.
  </footer>
</body>
</html>/* contact.html */

<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Contact</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600;800&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <section class="contact">
    <h3>Contact Me</h3>
    <p>Email: <a href="mailto:aminul@example.com">aminul@example.com</a></p>
    <p>GitHub: <a href="https://github.com/aminulshourob">@aminulshourob</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/aminulshourob">aminulshourob</a></p>
  </section>
  <footer>
    &copy; 2025 Aminul Haque Shourob.
  </footer>
</body>
</html>/* style.css / / This CSS file includes dark mode styles and animations, use previous CSS structure and extend it with page transition animation classes if needed. */

