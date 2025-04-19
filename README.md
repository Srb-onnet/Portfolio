<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600;800&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }body {
  font-family: 'Orbitron', 'Inter', sans-serif;
  background: radial-gradient(circle at center, #0c0d11 0%, #0b0c10 60%, #050509 100%);
  color: #c0d0e0;
  overflow-x: hidden;
  background-image: url('https://images.unsplash.com/photo-1603902363128-27f3d7a8d4bb?ixlib=rb-4.0.3&auto=format&fit=crop&w=1950&q=80');
  background-size: cover;
  background-attachment: fixed;
  background-blend-mode: overlay;
  background-position: center;
}

section {
  padding: 4rem 2rem;
  max-width: 1000px;
  margin: auto;
  backdrop-filter: blur(10px);
  background: rgba(12, 14, 18, 0.8);
  border-radius: 1rem;
  box-shadow: 0 0 25px rgba(0, 0, 0, 0.3);
}

.hero {
  text-align: center;
  padding-top: 3rem;
  animation: fadeInUp 1.5s ease-out;
}

.hero h2 {
  font-size: 3rem;
  margin-bottom: 1rem;
  color: #8cd1ff;
  font-weight: 800;
  letter-spacing: 1px;
  text-shadow: 0 0 5px rgba(140, 209, 255, 0.3);
  animation: flicker 3s infinite alternate;
}

.hero p {
  font-size: 1.2rem;
  max-width: 700px;
  margin: 0 auto;
  color: #a0b5cd;
  line-height: 1.6;
}

.btn {
  background: linear-gradient(135deg, #0c6cae, #004e7c);
  color: white;
  padding: 0.8rem 2rem;
  border: none;
  border-radius: 9999px;
  font-weight: 600;
  cursor: pointer;
  margin-top: 2rem;
  transition: background 0.3s, transform 0.3s;
  animation: pulse 2s infinite;
  box-shadow: 0 0 10px rgba(0, 128, 192, 0.4);
}

.btn:hover {
  background: linear-gradient(135deg, #008fc7, #006c9c);
  transform: scale(1.05);
}

.projects, .about, .contact {
  margin-top: 4rem;
  animation: fadeIn 2s ease-in forwards;
}

h3 {
  color: #9bc8f1;
  font-size: 2rem;
  margin-bottom: 1.5rem;
  text-align: center;
  font-weight: 700;
  letter-spacing: 1px;
  text-transform: uppercase;
  text-shadow: 0 0 8px rgba(155, 200, 241, 0.2);
}

.project-card {
  background: rgba(22, 24, 30, 0.9);
  padding: 1.5rem;
  border-radius: 1rem;
  margin-bottom: 2rem;
  box-shadow: 0 0 25px rgba(0, 0, 0, 0.4);
  transition: transform 0.5s, box-shadow 0.5s;
}

.project-card:hover {
  transform: translateY(-8px) scale(1.02);
  box-shadow: 0 0 30px rgba(0, 170, 255, 0.2);
}

.project-card h4 {
  color: #6fbfff;
  font-size: 1.5rem;
  margin-bottom: 0.5rem;
  text-shadow: 0 0 5px rgba(111, 191, 255, 0.2);
}

.project-card p {
  color: #a6bfd8;
  line-height: 1.5;
}

.contact p {
  text-align: center;
  margin: 0.5rem 0;
  color: #b5c7d8;
  font-size: 1rem;
}

footer {
  text-align: center;
  padding: 2rem;
  background: rgba(0, 0, 0, 0.9);
  color: #666f7a;
  font-size: 0.9rem;
  font-style: italic;
  text-shadow: 0 0 2px rgba(255,255,255,0.05);
}

.illustration {
  width: 80px;
  margin: 1rem auto;
  display: block;
  animation: floatCard 6s infinite alternate ease-in-out;
}

/* Animations */
@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

@keyframes fadeInUp {
  from { opacity: 0; transform: translateY(40px); }
  to { opacity: 1; transform: translateY(0); }
}

@keyframes pulse {
  0%, 100% { transform: scale(1); }
  50% { transform: scale(1.05); }
}

@keyframes flicker {
  0% { opacity: 1; }
  50% { opacity: 0.8; }
  100% { opacity: 1; }
}

@keyframes floatCard {
  from { transform: translateY(0px); }
  to { transform: translateY(-10px); }
}

  </style>
</head>
<body>
  <section class="hero">
    <img src="https://cdn-icons-png.flaticon.com/512/3017/3017511.png" alt="space icon" class="illustration">
    <h2>Hi, I'm Aminul</h2>
    <p>A full stack web developer with 4 years of experience, passionate about creating immersive web experiences that feel like a dream within a dream.</p>
    <button class="btn" onclick="document.getElementById('contact').scrollIntoView({behavior: 'smooth'})">Let's Talk</button>
  </section>  <section class="about" id="about">
    <h3>About Me</h3>
    <p style="text-align:center; max-width: 800px; margin: auto; color: #aac8e5; line-height: 1.6;">
      I'm a digital architect inspired by the multilayered storytelling of <em>Inception</em>. My goal is to craft digital dreams using technologies like JavaScript, React, Node.js, and more—blending aesthetics, logic, and immersive UI into a cinematic journey.
    </p>
  </section>  <section class="projects" id="projects">
    <h3>Featured Projects</h3>
    <div class="project-card">
      <h4>Dreamverse</h4>
      <p>A cinematic portfolio experience where users navigate layered UIs inspired by <em>Inception</em>'s dream levels. Built with React, GSAP, and CSS magic.</p>
    </div>
    <div class="project-card">
      <h4>InceptCommerce</h4>
      <p>An eCommerce universe with surreal transitions and smooth storytelling. Developed using Node, MongoDB, and animated routing techniques.</p>
    </div>
    <div class="project-card">
      <h4>MindMaze Blog</h4>
      <p>A blog platform set in a noir sci-fi theme for deep thinkers and dreamers. Markdown support, seamless syncing, and reflective UI.</p>
    </div>
  </section>  <section class="contact" id="contact">
    <h3>Contact Me</h3>
    <p>Email: <a href="mailto:aminul@example.com" style="color:#89d2ff">aminul@example.com</a></p>
    <p>GitHub: <a href="https://github.com/aminulshourob" target="_blank" style="color:#89d2ff">@aminulshourob</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/aminulshourob" target="_blank" style="color:#89d2ff">aminulshourob</a></p>
  </section>  <footer>
    &copy; 2025 Aminul Haque Shourob. "You're waiting for a dream. A coded dream."
  </footer>
</body>
</html>
