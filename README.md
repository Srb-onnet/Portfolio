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
  background: linear-gradient(145deg, #0f1116, #1a1d25);
  color: #e0e0e0;
  line-height: 1.6;
  overflow-x: hidden;
  background-image: radial-gradient(circle at 20% 30%, rgba(255,192,203,0.05), transparent 60%),
                    radial-gradient(circle at 80% 70%, rgba(255,182,193,0.05), transparent 60%);
  animation: backgroundFloat 30s infinite alternate;
}

section {
  padding: 4rem 2rem;
  max-width: 1000px;
  margin: auto;
}

.hero {
  text-align: center;
  padding-top: 3rem;
  animation: fadeInUp 1.5s ease-out;
  position: relative;
}

.hero h2 {
  font-size: 2.75rem;
  margin-bottom: 1rem;
  color: #fbcfe8;
  animation: flicker 3s infinite alternate;
}

.hero p {
  font-size: 1.2rem;
  max-width: 700px;
  margin: 0 auto;
  color: #a1a1aa;
}

.btn {
  background: #f472b6;
  color: #1a1d25;
  padding: 0.75rem 1.5rem;
  border: none;
  border-radius: 9999px;
  font-weight: 600;
  cursor: pointer;
  margin-top: 2rem;
  transition: background 0.3s, transform 0.3s;
  animation: pulse 2s infinite;
  box-shadow: 0 0 20px #f9a8d4;
}

.btn:hover {
  background: #f9a8d4;
  transform: scale(1.1);
}

.projects, .about, .contact {
  margin-top: 4rem;
  animation: fadeIn 2s ease-in forwards;
}

.projects h3, .about h3, .contact h3 {
  color: #fbcfe8;
  font-size: 2rem;
  margin-bottom: 1rem;
  text-align: center;
  animation: fadeInUp 1.5s ease-out;
  position: relative;
}

.projects h3::before, .about h3::before, .contact h3::before {
  content: '✨';
  position: absolute;
  left: -25px;
  animation: twinkle 1.5s infinite;
}

.project-card {
  background: #1f2937;
  padding: 1.5rem;
  border-radius: 1rem;
  margin-bottom: 2rem;
  box-shadow: 0 0 20px rgba(255, 255, 255, 0.04);
  transition: transform 0.5s, box-shadow 0.5s;
  animation: floatCard 3s ease-in-out infinite alternate;
}

.project-card:hover {
  transform: translateY(-8px) scale(1.02);
  box-shadow: 0 8px 30px rgba(255, 255, 255, 0.07);
}

.project-card h4 {
  color: #f9a8d4;
  font-size: 1.3rem;
  margin-bottom: 0.5rem;
}

.project-card p {
  color: #cbd5e1;
}

.contact p {
  text-align: center;
  margin: 0.5rem 0;
}

footer {
  text-align: center;
  padding: 2rem;
  background: #1a1d25;
  color: #71717a;
  font-size: 0.9rem;
  animation: fadeInUp 1.5s ease-out;
}

.illustration {
  width: 120px;
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
  50% { opacity: 0.7; }
  100% { opacity: 1; }
}

@keyframes twinkle {
  0%, 100% { opacity: 1; transform: scale(1); }
  50% { opacity: 0.4; transform: scale(1.3); }
}

@keyframes floatCard {
  from { transform: translateY(0px); }
  to { transform: translateY(-10px); }
}

@keyframes backgroundFloat {
  from { background-position: 0% 50%; }
  to { background-position: 100% 50%; }
}

  </style>
</head>
<body>
  <section class="hero">
    <img src="https://cdn-icons-png.flaticon.com/512/3468/3468379.png" alt="cute star" class="illustration">
    <h2>Hi, I'm Aminul</h2>
    <p>A full stack web developer with 4 years of experience, passionate about crafting beautiful and performant web applications with love and care.</p>
    <button class="btn" onclick="document.getElementById('contact').scrollIntoView({behavior: 'smooth'})">Let's Talk</button>
  </section>  <section class="about" id="about">
    <h3>About Me</h3>
    <img src="https://cdn-icons-png.flaticon.com/512/2202/2202112.png" alt="about" class="illustration">
    <p style="text-align:center; max-width: 800px; margin: auto; color: #cbd5e1;">
      I'm a Bangladeshi full stack developer who blends aesthetic UI with solid backend logic. From small startups to growing businesses, I've helped people build websites that are clean, functional, and joyful to use. I specialize in JavaScript, React, Node.js, Express, MongoDB, and love learning new tools.
    </p>
  </section>  <section class="projects" id="projects">
    <h3>Featured Projects</h3>
    <img src="https://cdn-icons-png.flaticon.com/512/857/857681.png" alt="projects" class="illustration">
    <div class="project-card">
      <h4>Sweetify - E-commerce Platform</h4>
      <p>A full-stack shopping platform for cute and sweet things. React, Node, MongoDB.</p>
    </div>
    <div class="project-card">
      <h4>ChillNotes - Personal Notes App</h4>
      <p>Relaxing UI to manage your thoughts and tasks. MERN Stack + JWT auth.</p>
    </div>
    <div class="project-card">
      <h4>Serene Blog</h4>
      <p>Minimal and smooth blog platform with Markdown support and a dark cinema-like reading experience.</p>
    </div>
  </section>  <section class="contact" id="contact">
    <h3>Contact Me</h3>
    <img src="https://cdn-icons-png.flaticon.com/512/4206/4206273.png" alt="contact" class="illustration">
    <p>Email: <a href="mailto:aminul@example.com" style="color:#f9a8d4">aminul@example.com</a></p>
    <p>GitHub: <a href="https://github.com/aminulshourob" target="_blank" style="color:#f9a8d4">@aminulshourob</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/aminulshourob" target="_blank" style="color:#f9a8d4">aminulshourob</a></p>
  </section>  <footer>
    &copy; 2025 Aminul Haque Shourob. Crafted with care.
  </footer>
</body>
</html>
