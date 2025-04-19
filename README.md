<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }body {
  background: linear-gradient(145deg, #0a0a0a, #1a1a1a);
  color: #e0e0e0;
  line-height: 1.6;
  overflow-x: hidden;
  background-image: url('https://images.unsplash.com/photo-1605032656457-3f3518e943a9?ixlib=rb-4.0.3&auto=format&fit=crop&w=1950&q=80');
  background-size: cover;
  background-attachment: fixed;
  background-blend-mode: overlay;
}

section {
  padding: 4rem 2rem;
  max-width: 1000px;
  margin: auto;
  backdrop-filter: blur(10px);
  background: rgba(0, 0, 0, 0.5);
  border-radius: 1rem;
}

.hero {
  text-align: center;
  padding-top: 3rem;
  animation: fadeInUp 1.5s ease-out;
}

.hero h2 {
  font-size: 3rem;
  margin-bottom: 1rem;
  color: #c9d1d9;
  animation: flicker 3s infinite alternate;
  font-weight: 700;
}

.hero p {
  font-size: 1.25rem;
  max-width: 700px;
  margin: 0 auto;
  color: #b0b0b0;
}

.btn {
  background: #1f6feb;
  color: white;
  padding: 0.75rem 1.5rem;
  border: none;
  border-radius: 9999px;
  font-weight: 600;
  cursor: pointer;
  margin-top: 2rem;
  transition: background 0.3s, transform 0.3s;
  animation: pulse 2s infinite;
}

.btn:hover {
  background: #388bfd;
  transform: scale(1.05);
}

.projects, .about, .contact {
  margin-top: 4rem;
  animation: fadeIn 2s ease-in forwards;
}

.projects h3, .about h3, .contact h3 {
  color: #f0f6fc;
  font-size: 2rem;
  margin-bottom: 1rem;
  text-align: center;
  animation: fadeInUp 1.5s ease-out;
}

.project-card {
  background: #0d1117;
  padding: 1.5rem;
  border-radius: 1rem;
  margin-bottom: 2rem;
  box-shadow: 0 0 20px rgba(255, 255, 255, 0.04);
  transition: transform 0.5s, box-shadow 0.5s;
}

.project-card:hover {
  transform: translateY(-8px) scale(1.02);
  box-shadow: 0 8px 30px rgba(255, 255, 255, 0.07);
}

.project-card h4 {
  color: #58a6ff;
  font-size: 1.3rem;
  margin-bottom: 0.5rem;
}

.project-card p {
  color: #8b949e;
}

.contact p {
  text-align: center;
  margin: 0.5rem 0;
}

footer {
  text-align: center;
  padding: 2rem;
  background: #0d1117;
  color: #71717a;
  font-size: 0.9rem;
  animation: fadeInUp 1.5s ease-out;
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
  50% { opacity: 0.85; }
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
    <img src="https://cdn-icons-png.flaticon.com/512/3468/3468379.png" alt="icon" class="illustration">
    <h2>Hi, I'm Aminul</h2>
    <p>A full stack web developer with 4 years of experience, passionate about crafting stunning web experiences that feel like a dream inside a dream.</p>
    <button class="btn" onclick="document.getElementById('contact').scrollIntoView({behavior: 'smooth'})">Let's Talk</button>
  </section>  <section class="about" id="about">
    <h3>About Me</h3>
    <p style="text-align:center; max-width: 800px; margin: auto; color: #cbd5e1;">
      I'm a dream-weaver in code, building seamless, immersive websites that pull users into elegant interfaces and intuitive logic. My expertise includes JavaScript, React, Node.js, and database wizardry. Inspired by cinematic visuals and layered experiences—just like in *Inception*.
    </p>
  </section>  <section class="projects" id="projects">
    <h3>Featured Projects</h3>
    <div class="project-card">
      <h4>Dreamverse</h4>
      <p>A cinematic portfolio space where users navigate layered UI like dream layers. Built with React, GSAP, and CSS magic.</p>
    </div>
    <div class="project-card">
      <h4>InceptCommerce</h4>
      <p>An eCommerce platform with a surreal product display flow. Node, MongoDB, and CSS transitions choreographed like a movie scene.</p>
    </div>
    <div class="project-card">
      <h4>MindMaze Blog</h4>
      <p>Write and reflect in a noir interface inspired by Nolan’s storytelling. Markdown, Auth, and cloud sync for maximum creativity.</p>
    </div>
  </section>  <section class="contact" id="contact">
    <h3>Contact Me</h3>
    <p>Email: <a href="mailto:aminul@example.com" style="color:#58a6ff">aminul@example.com</a></p>
    <p>GitHub: <a href="https://github.com/aminulshourob" target="_blank" style="color:#58a6ff">@aminulshourob</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/aminulshourob" target="_blank" style="color:#58a6ff">aminulshourob</a></p>
  </section>  <footer>
    &copy; 2025 Aminul Haque Shourob. Dream within a dream, coded.
  </footer>
</body>
</html>
