<!-- PREMIUM CYBERPUNK GITHUB PROFILE README -->
<!-- AUTHOR: darshanreddy-darshu -->
<!-- THEME: MIDNIGHT BLACK, ELECTRIC BLUE, NEON PURPLE, GLASSMORPHISM -->

<div align="center">

<!-- ==================== HERO SECTION ==================== -->
<!-- Inline Animated SVG Banner to ensure perfect cross-platform rendering without external dependencies -->
<svg viewBox="0 0 800 320" width="100%" style="background: #030303; border-radius: 16px; border: 1px solid rgba(0, 242, 254, 0.15); box-shadow: 0 20px 50px rgba(0,0,0,0.9); font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;">
  <defs>
    <!-- Gradients -->
    <linearGradient id="neonGlow" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#00f2fe" stop-opacity="1" />
      <stop offset="50%" stop-color="#4facfe" stop-opacity="1" />
      <stop offset="100%" stop-color="#000000" stop-opacity="1" />
    </linearGradient>
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00f2fe" />
      <stop offset="50%" stop-color="#9b51e0" />
      <stop offset="100%" stop-color="#00f2fe" />
    </linearGradient>
    <linearGradient id="gridGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#00f2fe" stop-opacity="0.05" />
      <stop offset="50%" stop-color="#9b51e0" stop-opacity="0.02" />
      <stop offset="100%" stop-color="#000000" stop-opacity="0" />
    </linearGradient>
    
    <!-- Filters for Glow Effect -->
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="8" result="blur" />
      <feMerge>
        <feMergeNode in="blur" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>
    <filter id="subtleGlow" x="-10%" y="-10%" width="120%" height="120%">
      <feGaussianBlur stdDeviation="3" result="blur" />
      <feMerge>
        <feMergeNode in="blur" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>

    <!-- Stylesheets for Custom Keyframe Animations -->
    <style>
      @keyframes pulseGrid {
        0% { transform: translateY(0px); }
        50% { transform: translateY(-10px); }
        100% { transform: translateY(0px); }
      }
      @keyframes floatParticle {
        0% { transform: translateY(0px) translateX(0px); opacity: 0.2; }
        50% { opacity: 0.8; }
        100% { transform: translateY(-60px) translateX(20px); opacity: 0; }
      }
      @keyframes textReveal {
        0% { stroke-dashoffset: 800; fill: rgba(0,0,0,0); }
        70% { fill: rgba(0,0,0,0); }
        100% { stroke-dashoffset: 0; fill: url(#textGrad); }
      }
      @keyframes waveMotion {
        0% { d: path("M 0 260 Q 200 240 400 260 T 800 260 L 800 320 L 0 320 Z"); }
        50% { d: path("M 0 260 Q 200 280 400 250 T 800 260 L 800 320 L 0 320 Z"); }
        100% { d: path("M 0 260 Q 200 240 400 260 T 800 260 L 800 320 L 0 320 Z"); }
      }
      @keyframes typing {
        0%, 100% { content: "Frontend Developer"; }
        25% { content: "Three.js Developer"; }
        50% { content: "Full Stack Learner"; }
        75% { content: "AI & ML Enthusiast"; }
      }
      @keyframes blink {
        50% { opacity: 0; }
      }
      .grid-bg { animation: pulseGrid 8s ease-in-out infinite; }
      .particle { animation: floatParticle 5s infinite linear; }
      .title-text {
        font-size: 46px; font-weight: 900; letter-spacing: 3px;
        stroke: #00f2fe; stroke-width: 1.5; stroke-dasharray: 800;
        animation: textReveal 3s cubic-bezier(0.19, 1, 0.22, 1) forwards;
      }
      .subtitle-box { font-size: 14px; fill: #a0aec0; font-weight: 400; letter-spacing: 2px; }
      .dynamic-text::after { content: ""; animation: typing 12s infinite; color: #00f2fe; font-weight: 600; }
      .cursor { animation: blink 0.8s infinite; fill: #00f2fe; }
      .wave { animation: waveMotion 6s ease-in-out infinite; }
    </style>
  </defs>

  <!-- Cyberpunk Grid Background -->
  <g class="grid-bg">
    <rect width="800" height="320" fill="url(#gridGrad)" />
    <path d="M0,40 H800 M0,80 H800 M0,120 H800 M0,160 H800 M0,200 H800 M0,240 H800 M0,280 H800" stroke="rgba(0, 242, 254, 0.03)" stroke-width="1" />
    <path d="M100,0 V320 M200,0 V320 M300,0 V320 M400,0 V320 M500,0 V320 M600,0 V320 M700,0 V320" stroke="rgba(155, 81, 224, 0.03)" stroke-width="1" />
  </g>

  <!-- Floating Particles -->
  <circle cx="150" cy="200" r="2" fill="#00f2fe" class="particle" style="animation-delay: 0s; animation-duration: 4s;" />
  <circle cx="650" cy="120" r="3" fill="#9b51e0" class="particle" style="animation-delay: 1.5s; animation-duration: 6s;" />
  <circle cx="300" cy="80" r="1.5" fill="#00f2fe" class="particle" style="animation-delay: 3s; animation-duration: 5s;" />
  <circle cx="500" cy="240" r="2.5" fill="#9b51e0" class="particle" style="animation-delay: 0.5s; animation-duration: 4.5s;" />

  <!-- Ambient Neon Subtle Orbs -->
  <circle cx="400" cy="140" r="90" fill="#00f2fe" opacity="0.04" filter="url(#glow)" />
  <circle cx="400" cy="140" r="50" fill="#9b51e0" opacity="0.04" filter="url(#glow)" />

  <!-- Identity Text -->
  <text x="50%" y="145" text-anchor="middle" class="title-text" filter="url(#subtleGlow)">DARSHAN REDDY</text>
  
  <!-- Typing Subtitle Container -->
  <g class="subtitle-box">
    <text x="50%" y="195" text-anchor="middle">
      <tspan class="dynamic-text"></tspan><tspan class="cursor" fill="#00f2fe">|</tspan>
    </text>
  </g>

  <!-- Futuristic Tech Accents -->
  <rect x="30" y="30" width="20" height="2" fill="#00f2fe" opacity="0.7" />
  <rect x="30" y="30" width="2" height="20" fill="#00f2fe" opacity="0.7" />
  <rect x="750" y="30" width="20" height="2" fill="#9b51e0" opacity="0.7" />
  <rect x="768" y="30" width="2" height="20" fill="#9b51e0" opacity="0.7" />
  
  <rect x="30" y="270" width="2" height="20" fill="#9b51e0" opacity="0.7" />
  <rect x="30" y="288" width="20" height="2" fill="#9b51e0" opacity="0.7" />
  <rect x="768" y="270" width="2" height="20" fill="#00f2fe" opacity="0.7" />
  <rect x="750" y="288" width="20" height="2" fill="#00f2fe" opacity="0.7" />

  <!-- Smooth Neon Wave Bottom Footer Connection -->
  <path class="wave" d="M 0 260 Q 200 240 400 260 T 800 260 L 800 320 L 0 320 Z" fill="url(#neonGlow)" opacity="0.08" />
  <path class="wave" d="M 0 265 Q 200 250 400 270 T 800 265 L 800 320 L 0 320 Z" fill="#00f2fe" opacity="0.04" />
</svg>

<br><br>

<!-- ==================== PREMIUM SEPARATOR ==================== -->
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png" width="100%" height="3px" alt="Separator" />

<br><br>

<!-- ==================== ABOUT ME SECTION (GLASSMORPHISM) ==================== -->
<table width="100%" style="border-collapse: collapse; background: linear-gradient(135deg, rgba(10, 10, 15, 0.7) 0%, rgba(3, 3, 5, 0.9) 100%); border-radius: 12px; border: 1px solid rgba(0, 242, 254, 0.15); box-shadow: 0 8px 32px 0 rgba(0, 242, 254, 0.05); backdrop-filter: blur(20px); -webkit-backdrop-filter: blur(20px);">
<tr>
<td style="padding: 40px;">
<h2 align="center" style="margin-top: 0; color: #00f2fe; letter-spacing: 2px; font-weight: 800;">⚡ EXECUTION CONTEXT</h2>
<p align="center" style="color: #8892b0; font-size: 15px; max-width: 650px; margin: 0 auto 30px auto; line-height: 1.6;">
  Crafting visually stunning, highly interactive web applications with immersive 3D graphics, premium layouts, and clean structural architecture.
</p>

```javascript
const developer = {
  profile:      "Darshan Reddy",
  location:     "Bengaluru, Karnataka, India",
  currentFocus: "Advanced Creative Frontend Architecture & WebGL Ecosystems",
  learning:     ["Three.js", "Shaders (GLSL)", "Advanced Python Engine Infrastructure", "AI & ML Frameworks"],
  goals:        "Build high-performance premium interfaces that bridge structural system logic and pure art",
  interests:    ["Cybersecurity & Cryptography", "Ethical Hacking", "Quantitative Asset Charting", "Next-Gen Web Design"]
};
</td>
</tr>
</table>
<!-- ==================== TECH STACK SECTION ==================== -->
<h2 align="center" style="color: #9b51e0; letter-spacing: 3px; font-weight: 800;">🌌 TECH STACK ARCHITECTURE</h2>
<p align="center" style="color: #64748b; font-size: 13px; margin-top: -10px; margin-bottom: 25px;">Engine components, execution frameworks, and layout systems optimized for fluid interactivity</p>
<div align="center">
<!-- Core Layout & Logic Engines -->
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" /> 
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" /> 
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" /> 
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" /> 
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />


<!-- Interactive & Frontend Frameworks -->
<img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white" alt="ThreeJS" /> 
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" /> 
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="NextJS" /> 
<img src="https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white" alt="Markdown" />


<!-- Backend, Database & Analytics -->
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="NodeJS" /> 
<img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="ExpressJS" /> 
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" /> 
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" /> 
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />


<!-- Operations, Terminals & System Environment -->
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" /> 
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /> 
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" /> 
<img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VSCode" /> 
<img src="https://img.shields.io/badge/NPM-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="NPM" /> 
<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma" />
</div>
<!-- ==================== PROJECTS ENGINE ==================== -->
<h2 align="center" style="color: #00f2fe; letter-spacing: 3px; font-weight: 800;">🎯 ARCHITECTURAL PROJECTS</h2>
<p align="center" style="color: #64748b; font-size: 13px; margin-top: -10px; margin-bottom: 30px;">Production-quality repositories and immersive creative assets</p>
<!-- Project Card 1: ASUS Website Clone -->
<table width="100%" style="border-collapse: collapse; margin-bottom: 20px; background: rgba(5, 5, 10, 0.6); border: 1px solid rgba(0, 242, 254, 0.1); border-radius: 8px;">
<tr>
<td style="padding: 24px;">
<div style="display: flex; justify-content: space-between; align-items: center;">
<h3 style="margin: 0; color: #fff; font-size: 18px;">💻 ASUS Website Clone</h3>
<img src="https://img.shields.io/badge/Status-Completed-success?style=flat-square&color=00f2fe" alt="Status" />
</div>
<p style="color: #8892b0; font-size: 14px; margin: 12px 0;">A pixel-perfect, hyper-responsive reconstruction of the ASUS enterprise ecosystem landing pages, mapping out meticulous layouts with structural precision and high-fidelity rendering mechanics.</p>
<p style="margin: 10px 0 16px 0;">
<img src="https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat&logo=html5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/Tailwind_CSS-%2338B2AC.svg?style=flat&logo=tailwind-css&logoColor=white" alt="Tailwind" />
<img src="https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=flat&logo=javascript&logoColor=black" alt="JS" />
</p>
<a href="https://github.com/darshanreddy-darshu" target="_blank"><img src="https://img.shields.io/badge/Live_Demo-000?style=for-the-badge&logo=vercel&logoColor=00f2fe&labelColor=111" alt="Demo" /></a> 
<a href="https://github.com/darshanreddy-darshu" target="_blank"><img src="https://img.shields.io/badge/Source_Code-000?style=for-the-badge&logo=github&logoColor=9b51e0&labelColor=111" alt="Source" /></a>
</td>
</tr>
</table>
<!-- Project Card 2: 3D Three.js Portfolio -->
<table width="100%" style="border-collapse: collapse; margin-bottom: 20px; background: rgba(5, 5, 10, 0.6); border: 1px solid rgba(155, 81, 224, 0.1); border-radius: 8px;">
<tr>
<td style="padding: 24px;">
<div style="display: flex; justify-content: space-between; align-items: center;">
<h3 style="margin: 0; color: #fff; font-size: 18px;">🔮 3D Three.js Portfolio</h3>
<img src="https://img.shields.io/badge/Status-Optimizing-blue?style=flat-square&color=9b51e0" alt="Status" />
</div>
<p style="color: #8892b0; font-size: 14px; margin: 12px 0;">An immersive, canvas-based three-dimensional portfolio space using custom vertex shaders, volumetric raymarching, lighting clusters, and responsive interactive orbital mechanics.</p>
<p style="margin: 10px 0 16px 0;">
<img src="https://img.shields.io/badge/Three.js-%23000000.svg?style=flat&logo=three.js&logoColor=white" alt="ThreeJS" />
<img src="https://img.shields.io/badge/Next.js-%23000000.svg?style=flat&logo=next.js&logoColor=white" alt="NextJS" />
<img src="https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=flat&logo=typescript&logoColor=white" alt="TS" />
</p>
<a href="https://github.com/darshanreddy-darshu" target="_blank"><img src="https://img.shields.io/badge/Live_Demo-000?style=for-the-badge&logo=vercel&logoColor=00f2fe&labelColor=111" alt="Demo" /></a> 
<a href="https://github.com/darshanreddy-darshu" target="_blank"><img src="https://img.shields.io/badge/Source_Code-000?style=for-the-badge&logo=github&logoColor=9b51e0&labelColor=111" alt="Source" /></a>
</td>
</tr>
</table>
<!-- Project Card 3: AI Projects Engine -->
<table width="100%" style="border-collapse: collapse; margin-bottom: 20px; background: rgba(5, 5, 10, 0.6); border: 1px solid rgba(0, 242, 254, 0.1); border-radius: 8px;">
<tr>
<td style="padding: 24px;">
<div style="display: flex; justify-content: space-between; align-items: center;">
<h3 style="margin: 0; color: #fff; font-size: 18px;">🧠 Deep Learning & AI Systems</h3>
<img src="https://img.shields.io/badge/Status-Active_R%26D-orange?style=flat-square" alt="Status" />
</div>
<p style="color: #8892b0; font-size: 14px; margin: 12px 0;">A series of local automation, data collection algorithms, and integrated machine learning evaluation modules written in Python utilizing clean matrix math and predictive modelling libraries.</p>
<p style="margin: 10px 0 16px 0;">
<img src="https://img.shields.io/badge/Python-%233776AB.svg?style=flat&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/NumPy-%23013243.svg?style=flat&logo=numpy&logoColor=white" alt="NumPy" />
<img src="https://img.shields.io/badge/MongoDB-%2347A248.svg?style=flat&logo=mongodb&logoColor=white" alt="MongoDB" />
</p>
<a href="https://github.com/darshanreddy-darshu" target="_blank"><img src="https://img.shields.io/badge/View_Repo-000?style=for-the-badge&logo=github&logoColor=00f2fe&labelColor=111" alt="Repo" /></a>
</td>
</tr>
</table>
<!-- Collapsible Section for Extra Experiments -->
<details>
<summary style="color: #9b51e0; font-weight: bold; cursor: pointer; margin-top: 15px; font-size: 14px; text-align: center;">📂 VIEW COMPONENT EXPERIMENTS & LAB PROJECTS</summary>


<table width="100%" style="border-collapse: collapse; background: rgba(3, 3, 5, 0.8); border: 1px dashed rgba(155, 81, 224, 0.3); border-radius: 8px;">
<tr>
<td style="padding: 20px;">
<strong>🕹️ Modern UI Components</strong>

<span style="color: #8892b0; font-size: 13px;">Advanced custom design assets featuring glassmorphic forms, smooth CSS transforms, and modular setups.</span>


<strong>🧪 Frontend Experiments (Steganography Vault Context)</strong>

<span style="color: #8892b0; font-size: 13px;">Secure sandboxed web architectures featuring local cryptographic canvas structures and byte-manipulation configurations.</span>
</td>
</tr>
</table>
</details>
<!-- ==================== LEARNING ROADMAP ==================== -->
<h2 align="center" style="color: #9b51e0; letter-spacing: 3px; font-weight: 800;">🗺️ ENGINE ROADMAP</h2>
<p align="center" style="color: #64748b; font-size: 13px; margin-top: -10px; margin-bottom: 25px;">Tracking proficiency across technological layers</p>
<div style="max-width: 600px; text-align: left; margin: 0 auto; font-family: monospace;">
<div style="margin-bottom: 15px;">
<div style="display: flex; justify-content: space-between; color: #a0aec0; font-size: 12px; margin-bottom: 4px;">
<span>FRONTEND ARCHITECTURE (NEXT.JS / TS / SCSS)</span>
<span style="color: #00f2fe;">95%</span>
</div>
<div style="background: rgba(255,255,255,0.05); height: 6px; border-radius: 3px; overflow: hidden; border: 1px solid rgba(0,242,254,0.15);">
<div style="background: linear-gradient(90deg, #4facfe 0%, #00f2fe 100%); height: 100%; width: 95%; border-radius: 3px;"></div>
</div>
</div>
<div style="margin-bottom: 15px;">
<div style="display: flex; justify-content: space-between; color: #a0aec0; font-size: 12px; margin-bottom: 4px;">
<span>INTERACTIVE WEBGL SYSTEMS (THREE.JS / GLSL)</span>
<span style="color: #9b51e0;">80%</span>
</div>
<div style="background: rgba(255,255,255,0.05); height: 6px; border-radius: 3px; overflow: hidden; border: 1px solid rgba(155,81,224,0.15);">
<div style="background: linear-gradient(90deg, #9b51e0 0%, #e051b8 100%); height: 100%; width: 80%; border-radius: 3px;"></div>
</div>
</div>
<div style="margin-bottom: 15px;">
<div style="display: flex; justify-content: space-between; color: #a0aec0; font-size: 12px; margin-bottom: 4px;">
<span>BACKEND DATA ENGINES (NODE.JS / MONGO)</span>
<span style="color: #00f2fe;">75%</span>
</div>
<div style="background: rgba(255,255,255,0.05); height: 6px; border-radius: 3px; overflow: hidden; border: 1px solid rgba(0,242,254,0.15);">
<div style="background: linear-gradient(90deg, #4facfe 0%, #00f2fe 100%); height: 100%; width: 75%; border-radius: 3px;"></div>
</div>
</div>
<div style="margin-bottom: 15px;">
<div style="display: flex; justify-content: space-between; color: #a0aec0; font-size: 12px; margin-bottom: 4px;">
<span>PYTHON ENGINE INFRASTRUCTURE & AI CORE</span>
<span style="color: #9b51e0;">70%</span>
</div>
<div style="background: rgba(255,255,255,0.05); height: 6px; border-radius: 3px; overflow: hidden; border: 1px solid rgba(155,81,224,0.15);">
<div style="background: linear-gradient(90deg, #9b51e0 0%, #e051b8 100%); height: 100%; width: 70%; border-radius: 3px;"></div>
</div>
</div>
</div>
<!-- ==================== METRICS & GITHUB STATS SECTION ==================== -->
<h2 align="center" style="color: #00f2fe; letter-spacing: 3px; font-weight: 800;">📊 DATA METRICS ENGINE</h2>
<p align="center" style="color: #64748b; font-size: 13px; margin-top: -10px; margin-bottom: 30px;">Live structural updates processing from the GitHub analytics hub</p>
<!-- Top Rows: Trophies, Core Stats, and Top Languages -->
<img src="https://github-profile-trophies.vercel.app/?username=darshanreddy-darshu&theme=cyberpunk&margin-w=8&margin-h=8&no-bg=true&no-frame=false" alt="Trophies" />
<div style="display: flex; flex-direction: column; gap: 15px; align-items: center; width: 100%;">
<img src="https://github-readme-stats.vercel.app/api?username=darshanreddy-darshu&show_icons=true&theme=cyberpunk&bg_color=030303&hide_border=false&border_color=00f2fe" width="410" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=darshanreddy-darshu&layout=compact&theme=cyberpunk&bg_color=030303&hide_border=false&border_color=9b51e0" width="410" alt="Top Languages" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=darshanreddy-darshu&theme=cyberpunk&background=030303&border=00f2fe" width="410" alt="Streak Stats" />
</div>
<!-- Contribution Snake Automation Integration Display Box -->
<table width="100%" style="border-collapse: collapse; background: #030303; border: 1px solid rgba(155, 81, 224, 0.2); border-radius: 8px;">
<tr>
<td style="padding: 20px;" align="center">
<span style="color: #a0aec0; font-size: 12px; letter-spacing: 1px; font-family: monospace;">EXECUTION STREAM: CONTRIBUTION GRAPH GENERATOR</span>


<!-- Relative paths render directly within the organization core profile view -->
<img src="https://raw.githubusercontent.com/darshanreddy-darshu/darshanreddy-darshu/output/github-contribution-grid-snake.svg" alt="Contribution Snake Matrix Grid" width="100%" style="max-width: 720px;" />
</td>
</tr>
</table>
<!-- Live Metadata Badges Counter Cluster -->
<p align="center">
<img src="https://img.shields.io/github/followers/darshanreddy-darshu?label=FOLLOWERS&style=for-the-badge&color=00f2fe&labelColor=111015" alt="Followers" /> 
<img src="https://img.shields.io/github/stars/darshanreddy-darshu?label=TOTAL%20STARS&style=for-the-badge&color=9b51e0&labelColor=111015" alt="Stars" /> 
<img src="https://komarev.com/normal-badge/?numerator=darshanreddy-darshu&style=for-the-badge&color=00f2fe&label=METRIC_VIEWS&labelColor=111015" alt="Profile Views" />
</p>
<!-- ==================== ACHIEVEMENTS & PHILOSOPHY ==================== -->
<table width="100%" style="border-collapse: collapse; background: linear-gradient(180deg, rgba(3,3,5,0.9) 0%, rgba(10,10,15,0.6) 100%); border-radius: 12px; border: 1px solid rgba(155, 81, 224, 0.15);">
<tr>
<td style="padding: 30px; text-align: center;">
<h3 style="margin: 0 0 15px 0; color: #9b51e0; letter-spacing: 1px;">💡 CORE DEV STATEMENT</h3>
<p style="color: #8892b0; font-size: 15px; font-style: italic; font-family: Georgia, serif; max-width: 550px; margin: 0 auto; line-height: 1.6;">
"The distance between imagination and absolute reality is bridged solely by pure structural logic and pixel performance optimization."
</p>
</td>
</tr>
</table>
<!-- ==================== TERMINAL RADAR CONTACT SECTION ==================== -->
<h2 align="center" style="color: #00f2fe; letter-spacing: 3px; font-weight: 800;">🛰️ NETWORK PROTOCOLS</h2>
<p align="center" style="color: #64748b; font-size: 13px; margin-top: -10px; margin-bottom: 25px;">Initialize connection sequences via standard communication relays</p>
<div align="center">
<a href="mailto:darshanreddy.dev@proton.me" target="_blank">
<img src="https://img.shields.io/badge/SECURE_EMAIL-000?style=for-the-badge&logo=protonmail&logoColor=00f2fe&labelColor=111&border_color=00f2fe" alt="Email Secure" />
</a>  
<a href="https://linkedin.com/in/darshan-reddy" target="_blank">
<img src="https://img.shields.io/badge/LINKEDIN_RELAY-000?style=for-the-badge&logo=linkedin&logoColor=9b51e0&labelColor=111" alt="LinkedIn Relay" />
</a>  
<a href="https://github.com/darshanreddy-darshu" target="_blank">
<img src="https://img.shields.io/badge/PORTFOLIO_HUB-000?style=for-the-badge&logo=three.js&logoColor=00f2fe&labelColor=111" alt="Portfolio Terminal" />
</a>
</div>
<!-- ==================== CUSTOM PREMIUM FOOTER ==================== -->
<svg viewBox="0 0 800 120" width="100%" style="background: #030303; border-radius: 12px; border-top: 1px solid rgba(155, 81, 224, 0.2); font-family: monospace;">
<defs>
<linearGradient id="footerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
<stop offset="0%" stop-color="#00f2fe" stop-opacity="0" />
<stop offset="50%" stop-color="#9b51e0" stop-opacity="1" />
<stop offset="100%" stop-color="#00f2fe" stop-opacity="0" />
</linearGradient>
<style>
@keyframes slowWave {
0% { transform: translateX(0px); }
100% { transform: translateX(-400px); }
}
@keyframes textGlow {
0%, 100% { fill: #a0aec0; text-shadow: 0 0 0px rgba(0,242,254,0); }
50% { fill: #00f2fe; text-shadow: 0 0 8px rgba(0,242,254,0.6); }
}
.footer-line { animation: slowWave 10s linear infinite; }
.thank-text { animation: textGlow 4s ease-in-out infinite; font-size: 12px; letter-spacing: 4px; font-weight: bold; }
</style>
</defs>
<!-- Glowing Divider Line Layout -->
<rect x="0" y="20" width="800" height="2" fill="url(#footerGrad)" />
<!-- Content -->
<text x="50%" y="65" text-anchor="middle" class="thank-text">=== SYSTEM TERMINATED // THANK YOU FOR VISITING ===</text>
<text x="50%" y="90" text-anchor="middle" fill="#4a5568" font-size="9" letter-spacing="1">AUTHENTICATED SIGNATURE CORE: DARSHANREDDY-DARSHU</text>
</svg>
<!-- ==================== OPTIONAL AUTOMATION BACKUP SYSTEM ==================== -->
<details>
<summary style="color: #64748b; font-size: 11px; cursor: pointer;">🛠️ CLICK TO VIEW SYSTEM AUTOMATION WORKFLOW CONFIGURATION</summary>


<p align="left" style="color: #8892b0; font-size: 12px;">If you choose to initialize the animated grid contribution snake module above, create a file named .github/workflows/snake.yml and paste this inside it:</p>
