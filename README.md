<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DreamSpace - Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Orbitron', sans-serif;
      background: linear-gradient(180deg, #0a0a1f 0%, #1a1a2e 100%);
      color: #e0e7ff;
    }
    .stars {
      background: url('https://www.transparenttextures.com/patterns/stardust.png');
      animation: moveStars 60s linear infinite;
    }
    @keyframes moveStars {
      0% {background-position: 0 0;}
      100% {background-position: -1000px 1000px;}
    }
  </style>
</head>
<body class="relative overflow-x-hidden">
  <div class="stars fixed w-full h-full top-0 left-0 opacity-20 z-0"></div>  <!-- Hero Section -->  <section class="min-h-screen flex flex-col justify-center items-center text-center relative z-10">
    <h1 class="text-5xl md:text-7xl font-bold bg-gradient-to-r from-blue-400 to-purple-600 bg-clip-text text-transparent animate-fade-in-up">SRB</h1>
    <p class="mt-4 text-xl text-blue-200 animate-fade-in">Dream Weaver | Code Alchemist</p>
  </section>  <!-- About Section -->  <section id="about" class="py-20 px-6 max-w-3xl mx-auto text-center">
    <h2 class="text-3xl mb-6 text-purple-300">About Me</h2>
    <p class="text-lg text-blue-100 italic">
      A wanderer through digital dreams,<br/>
      I craft illusions that live in screens.<br/>
      With code and cosmos intertwined,<br/>
      I leave a trace in space and time.
    </p>
  </section>  <!-- Projects Section -->  <section id="projects" class="py-20 px-6 bg-gradient-to-b from-black to-indigo-900">
    <h2 class="text-3xl text-center text-purple-300 mb-10">Projects</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-5xl mx-auto">
      <div class="relative group bg-black/30 backdrop-blur-md p-6 rounded-xl shadow-lg transition-all duration-500 hover:scale-105 hover:bg-purple-900/20">
        <h3 class="text-xl mb-2 text-blue-100">Dream Clock</h3>
        <p class="text-blue-300">A surreal timepiece where each second echoes in a different dimension.</p>
      </div>
      <div class="relative group bg-black/30 backdrop-blur-md p-6 rounded-xl shadow-lg transition-all duration-500 hover:scale-105 hover:bg-blue-900/20">
        <h3 class="text-xl mb-2 text-blue-100">Starboard</h3>
        <p class="text-blue-300">A galactic dashboard to visualize your life missions.</p>
      </div>
    </div>
  </section>  <!-- Skills Section -->  <section id="skills" class="py-20 px-6 text-center">
    <h2 class="text-3xl text-purple-300 mb-10">Skills</h2>
    <div class="flex flex-wrap justify-center gap-10">
      <div class="w-24 h-24 rounded-full border-4 border-blue-500 flex items-center justify-center text-blue-200">HTML</div>
      <div class="w-24 h-24 rounded-full border-4 border-purple-500 flex items-center justify-center text-purple-200">CSS</div>
      <div class="w-24 h-24 rounded-full border-4 border-indigo-500 flex items-center justify-center text-indigo-200">JS</div>
    </div>
  </section>  <!-- Contact Section -->  <section id="contact" class="py-20 px-6 bg-black text-center">
    <h2 class="text-3xl text-purple-300 mb-6">Contact Me</h2>
    <form class="max-w-md mx-auto space-y-4">
      <input type="text" placeholder="Your Name" class="w-full p-3 rounded bg-indigo-950 text-white placeholder-blue-300" />
      <input type="email" placeholder="Your Email" class="w-full p-3 rounded bg-indigo-950 text-white placeholder-blue-300" />
      <textarea rows="4" placeholder="Message" class="w-full p-3 rounded bg-indigo-950 text-white placeholder-blue-300"></textarea>
      <button type="submit" class="bg-gradient-to-r from-purple-600 to-blue-600 px-6 py-2 rounded-full text-white">Send Message</button>
    </form>
    <div class="mt-6 text-blue-300">
      <a href="#" class="mx-2 hover:text-white">Twitter</a>
      <a href="#" class="mx-2 hover:text-white">GitHub</a>
      <a href="#" class="mx-2 hover:text-white">LinkedIn</a>
    </div>
  </section>  <!-- Optional Background Sound -->  <audio id="bg-audio" autoplay loop volume="0.2">
    <source src="https://cdn.pixabay.com/download/audio/2022/02/23/audio_2b52f82324.mp3" type="audio/mpeg">
  </audio>
</body>
</html>
