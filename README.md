<!-- Animated SVG background + neon theme + 3D-ish glass project cards + social badges removed -->

<div align="center">
  <!-- Animated SVG background (subtle moving gradient) -->
  <svg width="100%" height="180" viewBox="0 0 1200 180" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" style="display:block; border-radius:12px; overflow:hidden;">
    <defs>
      <linearGradient id="g1" x1="0%" x2="100%" y1="0%" y2="100%">
        <stop offset="0%" stop-color="#7C3AED">
          <animate attributeName="stop-color" values="#7C3AED;#00D8FF;#7C3AED" dur="6s" repeatCount="indefinite" />
        </stop>
        <stop offset="50%" stop-color="#00D8FF">
          <animate attributeName="stop-color" values="#00D8FF;#C084FC;#00D8FF" dur="6s" repeatCount="indefinite" />
        </stop>
        <stop offset="100%" stop-color="#C084FC">
          <animate attributeName="stop-color" values="#C084FC;#7C3AED;#C084FC" dur="6s" repeatCount="indefinite" />
        </stop>
      </linearGradient>
      <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="18" result="coloredBlur" />
        <feMerge>
          <feMergeNode in="coloredBlur" />
          <feMergeNode in="SourceGraphic" />
        </feMerge>
      </filter>
    </defs>
    <rect x="0" y="0" width="1200" height="180" fill="url(#g1)" filter="url(#glow)" opacity="0.12" />
    <!-- moving circles -->
    <g opacity="0.14" fill="#ffffff">
      <circle cx="200" cy="40" r="80">
        <animate attributeName="cx" values="200;1000;200" dur="18s" repeatCount="indefinite" />
      </circle>
      <circle cx="900" cy="110" r="100">
        <animate attributeName="cx" values="900;150;900" dur="22s" repeatCount="indefinite" />
      </circle>
    </g>
  </svg>

  <!-- GIF + typing overlay -->
  <div style="display:flex;gap:18px;align-items:center;justify-content:center;margin-top:-80px">
    <div style="padding:10px;border-radius:14px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));box-shadow:0 10px 30px rgba(124,58,237,0.2), inset 0 1px 0 rgba(255,255,255,0.02);backdrop-filter: blur(6px);border:1px solid rgba(124,58,237,0.22);">
      <img src="https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif" alt="cat hello" width="220" style="display:block;border-radius:10px;" />
    </div>

    <div style="padding:8px 18px;border-radius:12px;background:linear-gradient(135deg, rgba(124,58,237,0.12), rgba(0,216,255,0.06));box-shadow:0 8px 30px rgba(124,58,237,0.16);border:1px solid rgba(124,58,237,0.2);min-width:380px;">
      <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=700&color=E9D5FF&center=true&vCenter=true&width=420&lines=Hi%2C+I%27m+GuardDog98;Developer+%2F+Game+Builder;Always+learning" alt="Typing SVG" />
      <p style="margin:8px 0 0;color:#E2E8F0;text-shadow:0 0 8px rgba(96,165,250,0.5)">Building clean, fast, and user‑friendly digital experiences — frontends, tools and playful prototypes.</p>
    </div>
  </div>
</div>



<p align="center" style="margin-top:18px;">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white" alt="Unity" />
</p>


---

### Featured projects — glass cards

<div style="display:flex;gap:14px;flex-wrap:wrap;justify-content:flex-start">

  <!-- Card 1 -->
  <div style="width:320px;padding:14px;border-radius:14px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border:1px solid rgba(124,58,237,0.18);box-shadow:0 18px 40px rgba(124,58,237,0.06), 0 6px 18px rgba(0,0,0,0.25);backdrop-filter: blur(6px);">
    <a href="https://github.com/GuardDog98/jele-runner-3d" style="text-decoration:none;color:inherit">
      <div style="height:140px;border-radius:10px;background:linear-gradient(135deg, rgba(124,58,237,0.14), rgba(0,216,255,0.06));display:flex;align-items:center;justify-content:center;font-weight:700;color:#FFF;">
        Jele Runner 3D
      </div>
      <p style="margin:10px 0 6px;color:#E6EEF8">3D offline single-player runner prototype built with Unity.</p>
      <p style="margin:0;color:#AAB8D6;font-size:13px">C# · Prototype · MIT</p>
    </a>
  </div>

  <!-- Card 2 -->
  <div style="width:320px;padding:14px;border-radius:14px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border:1px solid rgba(0,216,255,0.12);box-shadow:0 18px 40px rgba(0,216,255,0.06), 0 6px 18px rgba(0,0,0,0.25);backdrop-filter: blur(6px);">
    <a href="https://github.com/GuardDog98/jele-runner-android" style="text-decoration:none;color:inherit">
      <div style="height:140px;border-radius:10px;background:linear-gradient(135deg, rgba(0,216,255,0.12), rgba(124,58,237,0.06));display:flex;align-items:center;justify-content:center;font-weight:700;color:#FFF;">
        Jele Runner — Android
      </div>
      <p style="margin:10px 0 6px;color:#E6EEF8">Native Kotlin port of the Jele Runner prototype for Android.</p>
      <p style="margin:0;color:#AAB8D6;font-size:13px">Kotlin · Mobile · MIT</p>
    </a>
  </div>

</div>

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=GuardDog98&show_icons=true&theme=tokyonight&hide_border=true" alt="GuardDog98 GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=GuardDog98&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />
</p>


<p align="center" style="margin-top:8px;">
  <img src="https://komarev.com/ghpvc/?username=GuardDog98&color=7C3AED&style=flat-square" alt="Profile views" />
</p>
