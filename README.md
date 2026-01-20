<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Rakibul Islam | Portfolio</title>

  <!-- Tailwind CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- AOS Animation -->
  <link href="https://unpkg.com/aos@2.3.4/dist/aos.css" rel="stylesheet">
  <script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>

  <!-- Theme Script -->
  <script>
    function toggleTheme() {
      document.documentElement.classList.toggle('dark');
    }
  </script>

  <style>
    html.dark {
      background: #0f172a;
      color: #e5e7eb;
    }
  </style>
</head>
<body class="transition-all duration-500">

<!-- ================= HERO ================= -->
<section class="min-h-screen flex flex-col justify-center items-center text-center px-4">
  <h1 class="text-5xl md:text-6xl font-bold" data-aos="fade-down">
    Rakibul Islam
  </h1>
  <p class="mt-4 text-xl text-purple-500" data-aos="fade-up">
    BSc in CSE | AI • ML • Deep Learning
  </p>
  <div class="mt-6 flex gap-4" data-aos="zoom-in">
    <button onclick="toggleTheme()" class="px-5 py-2 rounded-xl bg-purple-600 text-white shadow">🌙 Toggle Theme</button>
    <a href="#projects" class="px-5 py-2 rounded-xl border">View Projects</a>
  </div>
</section>

<!-- ================= DASHBOARD STATS ================= -->
<section class="max-w-6xl mx-auto px-6 grid md:grid-cols-3 gap-6" data-aos="fade-up">
  <div class="p-6 rounded-2xl shadow hover:scale-105 transition">🎓<br><b>BSc in CSE</b><br>Southeast University</div>
  <div class="p-6 rounded-2xl shadow hover:scale-105 transition">🧠<br><b>AI & ML</b><br>Deep Learning</div>
  <div class="p-6 rounded-2xl shadow hover:scale-105 transition">🌐<br><b>Web Dev</b><br>Full Stack</div>
</section>

<!-- ================= SKILLS ================= -->
<section class="max-w-5xl mx-auto px-6 mt-20" data-aos="fade-up">
  <h2 class="text-3xl font-bold mb-6">🛠 Skills</h2>
  <div class="space-y-4">
    <div>
      <p>Python</p>
      <div class="w-full bg-gray-200 rounded-full h-3">
        <div class="bg-purple-600 h-3 rounded-full w-[90%]"></div>
      </div>
    </div>
    <div>
      <p>Machine Learning</p>
      <div class="w-full bg-gray-200 rounded-full h-3">
        <div class="bg-purple-600 h-3 rounded-full w-[85%]"></div>
      </div>
    </div>
    <div>
      <p>Web Development</p>
      <div class="w-full bg-gray-200 rounded-full h-3">
        <div class="bg-purple-600 h-3 rounded-full w-[80%]"></div>
      </div>
    </div>
  </div>
</section>

<!-- ================= PROJECTS ================= -->
<section id="projects" class="max-w-6xl mx-auto px-6 mt-20" data-aos="fade-up">
  <h2 class="text-3xl font-bold mb-6">🚀 Projects</h2>
  <div class="grid md:grid-cols-3 gap-6">
    <div class="p-6 rounded-2xl shadow hover:-translate-y-2 transition">🏙️ City of Gold<br><small>OpenGL Project</small></div>
    <div class="p-6 rounded-2xl shadow hover:-translate-y-2 transition">❤️ Heart Disease Prediction<br><small>AI Model</small></div>
    <div class="p-6 rounded-2xl shadow hover:-translate-y-2 transition">📊 System Monitor<br><small>Python App</small></div>
  </div>
</section>

<!-- ================= GITHUB STATS ================= -->
<section class="max-w-6xl mx-auto px-6 mt-20 text-center" data-aos="fade-up">
  <h2 class="text-3xl font-bold mb-6">📈 GitHub Stats</h2>
  <img class="mx-auto" src="https://github-readme-stats.vercel.app/api?username=rishuvro&show_icons=true&theme=github_dark" />
  <img class="mx-auto mt-4" src="https://github-readme-streak-stats.herokuapp.com/?user=rishuvro&theme=github_dark" />
</section>

<!-- ================= FOOTER ================= -->
<footer class="text-center py-10 mt-20">
  <p>👀 Visitors</p>
  <img class="mx-auto" src="https://komarev.com/ghpvc/?username=rishuvro&color=blueviolet" />
  <p class="mt-4">© 2026 Rakibul Islam</p>
</footer>

<script>AOS.init({ once: true });</script>
</body>
</html>
