<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>amiay — Full-Stack Web Developer</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body { background: #18192b; font-family: 'JetBrains Mono', monospace; }
    .fade-in { animation: fadeIn 1.2s cubic-bezier(.4,0,.2,1); }
    @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
    .glass {
      background: rgba(24, 25, 43, 0.85);
      box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.18);
      backdrop-filter: blur(8px);
      border-radius: 1.25rem;
      border: 1px solid rgba(80, 80, 120, 0.18);
    }
    .gradient-bg {
      position: fixed;
      inset: 0;
      z-index: -1;
      background: radial-gradient(ellipse at 60% 10%, #3b2f80 0%, #18192b 70%);
      animation: gradientMove 12s ease-in-out infinite alternate;
    }
    @keyframes gradientMove {
      0% { background-position: 60% 10%; }
      100% { background-position: 40% 90%; }
    }
    .glow {
      text-shadow: 0 2px 16px #7f5cff44, 0 1px 0 #fff2;
    }
    .icon-shadow {
      filter: drop-shadow(0 2px 8px #7f5cff44);
    }
    .section-title {
      letter-spacing: 1px;
    }
    .badge {
      font-size: 0.85em;
      padding: 0.2em 0.7em;
      border-radius: 0.5em;
      font-weight: bold;
      background: #23243a;
      color: #bcbcff;
      margin-right: 0.5em;
    }
    .project-card {
      background: rgba(36, 37, 60, 0.85);
      border: 1px solid #23243a;
      border-radius: 1em;
      padding: 1.2em 1.5em;
      margin-bottom: 1.2em;
      box-shadow: 0 2px 12px 0 #23243a33;
      transition: transform 0.15s;
    }
    .project-card:hover {
      transform: scale(1.015);
      border-color: #7f5cff;
    }
  </style>
</head>
<body class="min-h-screen flex flex-col justify-between text-gray-200">
  <div class="gradient-bg"></div>
  <main id="main-content" class="fade-in">
    <section class="py-12 px-4 max-w-3xl mx-auto">
      <div class="flex items-center gap-3 mb-8">
        <svg width="38" height="38" fill="none" viewBox="0 0 38 38" class="icon-shadow"><circle cx="19" cy="19" r="19" fill="#7f5cff"/><text x="50%" y="55%" text-anchor="middle" fill="#fff" font-size="18" font-family="JetBrains Mono, monospace" dy=".3em">AY</text></svg>
        <h1 class="text-4xl md:text-5xl font-extrabold glow text-violet-300 tracking-tight">AMIAY</h1>
      </div>
      <p class="mb-8 text-lg text-gray-400 text-center">Hey there 👋, I'm a <span class="text-violet-300 font-semibold">Full-Stack Web Developer</span> passionate about building fast, clean and scalable web applications.<br>I love solving complex problems and turning ideas into elegant solutions.</p>

      <div class="glass p-7 shadow-xl border border-violet-900/30 mb-12">
        <h2 class="text-2xl font-bold text-violet-200 mb-3 section-title">🧠 About Me</h2>
        <ul class="list-disc pl-6 text-base text-gray-300 space-y-1">
          <li>🔭 I’m currently working as a <b>Full-Stack Web Developer</b></li>
          <li>⚙️ My main stacks: <b>PHP</b> + <b>Express.js</b></li>
          <li>💡 I also code with: <b>JavaScript</b>, <b>C#</b>, <b>Node.js</b>, <b>MySQL</b>, <b>MongoDB</b>, <b>HTML/CSS</b>, and more...</li>
          <li>🧩 I enjoy exploring new technologies, tools, and best practices in development</li>
          <li>🌍 I speak French natively, and I work fluently in English</li>
          <li>🧙‍♂️ Slightly nerdy. Probably tweaking a <code>config.json</code> file while you read this...</li>
        </ul>
      </div>

      <div class="glass p-7 shadow-xl border border-violet-900/30 mb-12">
        <h2 class="text-2xl font-bold text-violet-200 mb-3 section-title">🛠️ Technologies & Tools</h2>
        <div class="flex flex-wrap gap-4 items-center justify-center">
          <img src="https://skillicons.dev/icons?i=php,express,js,nodejs,html,css,mysql,git,linux,vscode" alt="Tech stack" class="h-12"/>
        </div>
      </div>

      <div class="glass p-7 shadow-xl border border-violet-900/30 mb-12">
        <h2 class="text-2xl font-bold text-violet-200 mb-3 section-title">📈 GitHub Stats</h2>
        <div class="flex flex-col items-center gap-4">
          <img src="https://github-readme-stats.vercel.app/api?username=amiayweb&show_icons=true&theme=radical&count_private=true" alt="GitHub stats" class="rounded-lg shadow"/>
          <img src="https://github-readme-streak-stats.herokuapp.com?user=amiayweb&theme=radical" alt="GitHub streak stats" class="rounded-lg shadow"/>
        </div>
      </div>

      <div class="glass p-7 shadow-xl border border-violet-900/30 mb-12">
        <h2 class="text-2xl font-bold text-violet-200 mb-3 section-title">🤝 Let’s Connect</h2>
        <div class="flex flex-wrap gap-4 items-center justify-center">
          <a href="mailto:tvamiay@gmail.com" class="inline-flex items-center gap-2 px-4 py-2 rounded-full font-semibold text-white bg-[#D14836] hover:bg-[#b0301b] transition text-base">
            <svg width="20" height="20" fill="none" viewBox="0 0 32 32"><rect width="32" height="32" rx="16" fill="#D14836"/><path d="M8 10.5v11a1.5 1.5 0 001.5 1.5h13a1.5 1.5 0 001.5-1.5v-11a1.5 1.5 0 00-1.5-1.5h-13A1.5 1.5 0 008 10.5zm2.06.5l5.44 4.36a1.5 1.5 0 001.88 0l5.44-4.36" fill="#fff"/></svg>
            Email
          </a>
        </div>
      </div>

      <div class="glass p-7 shadow-xl border border-violet-900/30 mb-12">
        <h2 class="text-2xl font-bold text-violet-200 mb-3 section-title">📂 Featured Projects</h2>
        <div class="text-gray-400 italic">soon</div>
      </div>
    </section>
  </main>

  <footer class="mt-12 py-6 bg-[#18192b] border-t border-violet-900/40 text-center text-gray-400 text-sm">
    <div class="flex flex-col items-center gap-2">
      <span class="flex items-center gap-2"><svg width="18" height="18" fill="none" viewBox="0 0 38 38"><circle cx="9" cy="9" r="9" fill="#7f5cff"/><text x="50%" y="55%" text-anchor="middle" fill="#fff" font-size="10" font-family="JetBrains Mono, monospace" dy=".3em">AY</text></svg> <span class="font-bold text-violet-300">amiay</span> <span class="text-xs">Full-Stack Web Developer</span></span>
      <span class="text-xs">Made with <span class="text-pink-400">♥</span> by amiay</span>
    </div>
  </footer>
</body>
</html> 
