<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Aminul Haque Shourob | Portfolio</title>
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
}

header {
  background: rgba(26, 29, 37, 0.95);
  padding: 1.5rem 4rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  box-shadow: 0 4px 30px rgba(0,0,0,0.2);
  position: sticky;
  top: 0;
  z-index: 1000;
  animation: slideDown 1s ease-out;
}

header h1 {
  font-size: 1.8rem;
  color: #f9a8d4;
  animation: fadeIn 1.5s ease-in-out;
}

nav a {
  color: #cbd5e1;
  margin-left: 1.5rem;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.3s, transform 0.3s;
  animation: fadeIn 2s ease-in-out;
}

nav a:hover {
  color: #f9a8d4;
  transform: scale(1.05);
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
}

.project-card {
  background: #1f2937;
  padding: 1.5rem;
  border-radius: 1rem;
  margin-bottom: 2rem;
  box-shadow: 0 0 20px rgba(255, 255, 255, 0.04);
  transition: transform 0.5s, box-shadow 0.5s;
  animation: slideUp 1s ease-out;
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

/* Animations */
@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

@keyframes fadeInUp {
  from { opacity: 0; transform: translateY(40px); }
  to { opacity: 1; transform: translateY(0); }
}

@keyframes slideUp {
  from { opacity: 0; transform: translateY(100px); }
  to { opacity: 1; transform: translateY(0); }
}

@keyframes slideDown {
  from { transform: translateY(-100%); }
  to { transform: translateY(0); }
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

  </style>
</head>
<body>
  <header>
    <h1>Aminul Haque Shourob</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>  <section class="hero">
    <h2>Hi, I'm Aminul</h2>
    <p>A full stack web developer with 4 years of experience, passionate about crafting beautiful and performant web applications with love and care.</p>
    <button class="btn" onclick="document.getElementById('contact').scrollIntoView({behavior: 'smooth'})">Let's Talk</button>
  </section>  <section class="about" id="about">
    <h3>About Me</h3>
    <p style="text-align:center; max-width: 800px; margin: auto; color: #cbd5e1;">
      I'm a Bangladeshi full stack developer who blends aesthetic UI with solid backend logic. From small startups to growing businesses, I've helped people build websites that are clean, functional, and joyful to use. I specialize in JavaScript, React, Node.js, Express, MongoDB, and love learning new tools.
    </p>
  </section>  <section class="projects" id="projects">
    <h3>Featured Projects</h3>
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
    <p>Email: <a href="mailto:aminul@example.com" style="color:#f9a8d4">aminul@example.com</a></p>
    <p>GitHub: <a href="https://github.com/aminulshourob" target="_blank" style="color:#f9a8d4">@aminulshourob</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/aminulshourob" target="_blank" style="color:#f9a8d4">aminulshourob</a></p>
  </section>  <footer>
    &copy; 2025 Aminul Haque Shourob. Crafted with care.
  </footer>  <script>
    // Scroll reveal effect
    const sections = document.querySelectorAll("section");
    const options = {
      threshold: 0.1
    };

    const reveal = new IntersectionObserver(function(entries, observer) {
      entries.forEach(entry => {
        if (!entry.isIntersecting) return;
        entry.target.classList.add("visible");
        observer.unobserve(entry.target);
      });
    }, options);

    sections.forEach(section => {
      reveal.observe(section);
    });
  </script></body>
</html>
