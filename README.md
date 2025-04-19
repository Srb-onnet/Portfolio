<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Aminul Haque Shourob | Cinematic Portfolio</title>
  <style>
    :root {
      --bg-color: #0a0a0f;
      --text-color: #e0e0e0;
      --accent-color: #0077ff;
      --card-bg: #1a1a2e;
      --hover-bg: #292941;
      --gold: #bfa046;
    }* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html, body {
  scroll-behavior: smooth;
  background: var(--bg-color);
  color: var(--text-color);
  font-family: 'Orbitron', sans-serif;
}

header {
  position: fixed;
  width: 100%;
  top: 0;
  left: 0;
  background: rgba(10, 10, 15, 0.95);
  z-index: 1000;
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  backdrop-filter: blur(10px);
}

nav ul {
  list-style: none;
  display: flex;
  gap: 1.5rem;
}

nav ul li a {
  color: var(--text-color);
  text-decoration: none;
  font-weight: 500;
}

nav ul li a:hover {
  color: var(--gold);
}

#darkModeToggle {
  background: none;
  border: 1px solid var(--accent-color);
  color: var(--text-color);
  padding: 0.4rem 0.8rem;
  cursor: pointer;
  border-radius: 5px;
}

.section {
  padding: 100px 20px;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.parallax {
  background: linear-gradient(rgba(10,10,15,0.8), rgba(10,10,15,0.8)), url('https://images.unsplash.com/photo-1518770660439-4636190af475') no-repeat center center fixed;
  background-size: cover;
}

h2 {
  font-size: 2.5rem;
  color: var(--gold);
  margin-bottom: 1rem;
}

p, li {
  font-family: 'Roboto Mono', monospace;
  font-size: 1.1rem;
  line-height: 1.6;
}

.projects-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
}

.card {
  background: var(--card-bg);
  padding: 2rem;
  border-radius: 10px;
  width: 250px;
  transition: background 0.3s, transform 0.3s;
}

.card:hover {
  background: var(--hover-bg);
  transform: translateY(-5px);
}

.skills-list {
  list-style: none;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 1rem;
  max-width: 600px;
}

.btn {
  background: var(--accent-color);
  padding: 0.6rem 1.2rem;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  text-decoration: none;
}

form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  width: 100%;
  max-width: 500px;
}

input, textarea {
  padding: 0.8rem;
  background: var(--card-bg);
  border: none;
  color: white;
  border-radius: 5px;
}

footer {
  text-align: center;
  padding: 2rem;
  background: #0a0a0f;
  font-size: 0.9rem;
  opacity: 0.7;
}

  </style>
  <script>
    document.addEventListener('DOMContentLoaded', () => {
      const toggle = document.getElementById('darkModeToggle');
      toggle.addEventListener('click', () => {
        document.body.classList.toggle('light');
      });
    });
  </script>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Roboto+Mono&display=swap" rel="stylesheet">
</head>
<body>
  <div id="particles-js"></div>
  <header>
    <nav>
      <h1 class="logo">MyPortfolio</h1>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About Me</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#resume">Resume</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
      <button id="darkModeToggle">Toggle</button>
    </nav>
  </header>  <section id="home" class="section parallax">
    <div class="content">
      <h2>Welcome to My Dreamscape</h2>
      <p>Cinematic, futuristic, and minimalist</p>
    </div>
  </section>  <section id="about" class="section">
    <h2>About Me</h2>
    <p>I'm Aminul Haque Shourob, a web developer with 4 years of experience. I specialize in creating immersive digital experiences that blend mystery with minimalism, inspired by the complexity and elegance of Inception.</p>
  </section>  <section id="projects" class="section">
    <h2>Projects</h2>
    <div class="projects-container">
      <div class="card">Project 1</div>
      <div class="card">Project 2</div>
      <div class="card">Project 3</div>
    </div>
  </section>  <section id="skills" class="section">
    <h2>Skills</h2>
    <ul class="skills-list">
      <li>HTML & CSS</li>
      <li>JavaScript</li>
      <li>React</li>
      <li>Three.js</li>
    </ul>
  </section>  <section id="resume" class="section">
    <h2>Resume</h2>
    <a href="resume.pdf" download class="btn">Download PDF</a>
  </section>  <section id="contact" class="section">
    <h2>Contact</h2>
    <form>
      <input type="text" placeholder="Name" required />
      <input type="email" placeholder="Email" required />
      <textarea placeholder="Your message"></textarea>
      <button type="submit">Send</button>
    </form>
  </section>  <footer>
    <p>&copy; 2025 Aminul Haque Shourob. Dream a little bigger.</p>
  </footer>  <script src="https://cdn.jsdelivr.net/npm/particles.js"></script></body>
</html>
