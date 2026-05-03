<div align="center">

<!-- ═══════════════════════════════════════════════════════════════════
NIKE DESIGN SYSTEM — GitHub Profile README (CSS-workaround edition)
GitHub strips style="…" on HTML elements, but SVG has full CSS control.
Strategy: SVG for all styled UI | shields.io for badges | tables w/ bgcolor
Tokens: ink #111111 | canvas #ffffff | soft-cloud #f5f5f5 | sale #d30005
═══════════════════════════════════════════════════════════════════ -->

<!-- ─────────────────────────────────────────────────────────────────
CAMPAIGN HERO — full-bleed editorial SVG
Composition: geometric backdrop + display lockup + pill CTA
───────────────────────────────────────────────────────────────── -->
<svg width="100%" viewBox="0 0 960 480" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      .bg { fill: #111111; }
      .geo { fill: none; stroke: #ffffff; }
      .headline { font-family: 'Impact', 'Arial Black', 'Helvetica Neue', sans-serif; font-size: 88px; fill: #ffffff; font-weight: 700; letter-spacing: -2px; }
      .subhead { font-family: 'Segoe UI', 'Helvetica Neue', Arial, sans-serif; font-size: 22px; fill: #9e9ea0; font-weight: 600; }
      .tag { font-family: 'Segoe UI', 'Helvetica Neue', Arial, sans-serif; font-size: 16px; fill: #707072; font-weight: 500; }
      .pill-bg { fill: #ffffff; rx: 30; ry: 30; }
      .pill-text { font-family: 'Segoe UI', 'Helvetica Neue', Arial, sans-serif; font-size: 16px; fill: #111111; font-weight: 600; }
      .pill-bg-soft { fill: #f5f5f5; rx: 30; ry: 30; }
      .pill-text-soft { font-family: 'Segoe UI', 'Helvetica Neue', Arial, sans-serif; font-size: 16px; fill: #111111; font-weight: 600; }
    </style>
  </defs>

  <!-- canvas -->
  <rect width="960" height="480" class="bg"/>

  <!-- editorial geometry — Nike campaign stand-in -->
  <circle cx="820" cy="420" r="360" class="geo" stroke-opacity="0.03" stroke-width="1.5"/>
  <circle cx="840" cy="400" r="260" class="geo" stroke-opacity="0.04" stroke-width="1"/>
  <circle cx="860" cy="380" r="160" class="geo" stroke-opacity="0.06" stroke-width="1"/>
  <circle cx="880" cy="360" r="80"  class="geo" stroke-opacity="0.08" stroke-width="1"/>

  <line x1="0" y1="240" x2="960" y2="240" class="geo" stroke-opacity="0.02" stroke-width="1"/>
  <line x1="0" y1="360" x2="960" y2="360" class="geo" stroke-opacity="0.015" stroke-width="1"/>

  <!-- angled accent -->
  <line x1="600" y1="0" x2="960" y2="360" class="geo" stroke-opacity="0.02" stroke-width="1"/>

  <!-- display headline -->
  <text x="80" y="195" class="headline">ADITYA</text>
  <text x="80" y="275" class="headline">ANAND</text>

  <!-- subhead -->
  <text x="80" y="325" class="subhead">FULL-STACK DEVELOPER  ·  OPEN SOURCE  ·  SYSTEMS</text>

  <!-- tagline -->
  <text x="80" y="360" class="tag">Code as craft. Performance as language.</text>

  <!-- CTA pills — Nike button pair -->
  <!-- primary pill: GET IN TOUCH -->
  <rect x="80" y="400" width="190" height="48" class="pill-bg"/>
  <text x="175" y="430" class="pill-text" text-anchor="middle">GET IN TOUCH</text>

  <!-- secondary pill: LINKEDIN -->
  <rect x="286" y="400" width="170" height="48" class="pill-bg-soft"/>
  <text x="371" y="430" class="pill-text-soft" text-anchor="middle">LINKEDIN</text>

  <!-- view repos pill -->
  <rect x="472" y="400" width="170" height="48" class="pill-bg-soft"/>
  <text x="557" y="430" class="pill-text-soft" text-anchor="middle">VIEW REPOS</text>

</svg>

<!-- NAVIGATION — image map not supported; use shields.io badges as clickable pills -->
<br>
<a href="mailto:aditya.anand@monks.com">
  <img src="https://img.shields.io/badge/GET%20IN%20TOUCH-111111?style=for-the-badge&logo=gmail&logoColor=white&labelColor=111111&color=111111" height="40" alt="Email"/>
</a>
&nbsp;
<a href="https://linkedin.com/in/adityaArise">
  <img src="https://img.shields.io/badge/LINKEDIN-f5f5f5?style=for-the-badge&logo=linkedin&logoColor=111111&labelColor=f5f5f5&color=f5f5f5" height="40" alt="LinkedIn"/>
</a>
&nbsp;
<a href="https://github.com/adityaanand0001?tab=repositories">
  <img src="https://img.shields.io/badge/REPOS-f5f5f5?style=for-the-badge&logo=github&logoColor=111111&labelColor=f5f5f5&color=f5f5f5" height="40" alt="Repos"/>
</a>

<br><br>

<!-- ─────────────────────────────────────────────────────────────────
TECH STACK — filter-chip pills via shields.io
Active: ink bg, white text | Default: soft-cloud bg, ink text
───────────────────────────────────────────────────────────────── -->

<!-- SECTION HEADER SVG -->
<svg width="960" height="48" viewBox="0 0 960 48" xmlns="http://www.w3.org/2000/svg">
  <style>
    .label { font-family: 'Segoe UI','Helvetica Neue',Arial,sans-serif; font-size: 18px; fill: #111111; font-weight: 600; }
    .rule { stroke: #e5e5e5; stroke-width: 1; }
  </style>
  <text x="0" y="24" class="label">TECH STACK</text>
  <line x1="0" y1="44" x2="960" y2="44" class="rule"/>
</svg>

<br>

<!-- Primary skills — ink pills (active filter-chip) -->
<p>
  <img src="https://img.shields.io/badge/REACT-111111?style=for-the-badge&logo=react&logoColor=white&labelColor=111111&color=111111" height="34">
  <img src="https://img.shields.io/badge/NEXT.JS-111111?style=for-the-badge&logo=nextdotjs&logoColor=white&labelColor=111111&color=111111" height="34">
  <img src="https://img.shields.io/badge/TYPESCRIPT-111111?style=for-the-badge&logo=typescript&logoColor=white&labelColor=111111&color=111111" height="34">
  <img src="https://img.shields.io/badge/NODE.JS-111111?style=for-the-badge&logo=nodedotjs&logoColor=white&labelColor=111111&color=111111" height="34">
  <img src="https://img.shields.io/badge/PYTHON-111111?style=for-the-badge&logo=python&logoColor=white&labelColor=111111&color=111111" height="34">
</p>

<!-- Secondary skills — soft-cloud pills (default filter-chip) -->
<p>
  <img src="https://img.shields.io/badge/DOCKER-f5f5f5?style=for-the-badge&logo=docker&logoColor=111111&labelColor=f5f5f5&color=f5f5f5" height="34">
  <img src="https://img.shields.io/badge/AWS-f5f5f5?style=for-the-badge&logo=amazonwebservices&logoColor=111111&labelColor=f5f5f5&color=f5f5f5" height="34">
  <img src="https://img.shields.io/badge/MONGODB-f5f5f5?style=for-the-badge&logo=mongodb&logoColor=111111&labelColor=f5f5f5&color=f5f5f5" height="34">
  <img src="https://img.shields.io/badge/POSTGRESQL-f5f5f5?style=for-the-badge&logo=postgresql&logoColor=111111&labelColor=f5f5f5&color=f5f5f5" height="34">
  <img src="https://img.shields.io/badge/TAILWIND-f5f5f5?style=for-the-badge&logo=tailwindcss&logoColor=111111&labelColor=f5f5f5&color=f5f5f5" height="34">
</p>
<p>
  <img src="https://img.shields.io/badge/GO-f5f5f5?style=for-the-badge&logo=go&logoColor=111111&labelColor=f5f5f5&color=f5f5f5" height="34">
  <img src="https://img.shields.io/badge/GRAPHQL-f5f5f5?style=for-the-badge&logo=graphql&logoColor=111111&labelColor=f5f5f5&color=f5f5f5" height="34">
  <img src="https://img.shields.io/badge/GIT-f5f5f5?style=for-the-badge&logo=git&logoColor=111111&labelColor=f5f5f5&color=f5f5f5" height="34">
  <img src="https://img.shields.io/badge/LINUX-f5f5f5?style=for-the-badge&logo=linux&logoColor=111111&labelColor=f5f5f5&color=f5f5f5" height="34">
  <img src="https://img.shields.io/badge/FIGMA-f5f5f5?style=for-the-badge&logo=figma&logoColor=111111&labelColor=f5f5f5&color=f5f5f5" height="34">
</p>

<br>

<!-- ─────────────────────────────────────────────────────────────────
PERFORMANCE — stats cards in soft-cloud bg
Uses github-readme-stats with Nike palette params
───────────────────────────────────────────────────────────────── -->
<svg width="960" height="48" viewBox="0 0 960 48" xmlns="http://www.w3.org/2000/svg">
  <style>
    .label { font-family: 'Segoe UI','Helvetica Neue',Arial,sans-serif; font-size: 18px; fill: #111111; font-weight: 600; }
    .rule { stroke: #e5e5e5; stroke-width: 1; }
  </style>
  <text x="0" y="24" class="label">PERFORMANCE</text>
  <line x1="0" y1="44" x2="960" y2="44" class="rule"/>
</svg>

<br>

<a href="https://github.com/adityaanand0001">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=adityaanand0001&show_icons=true&hide_border=true&bg_color=f5f5f5&title_color=111111&text_color=707072&icon_color=111111&ring_color=111111&hide_title=true&count_private=true&include_all_commits=true">
</a>
<a href="https://github.com/adityaanand0001">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=adityaanand0001&layout=compact&hide_border=true&bg_color=f5f5f5&title_color=111111&text_color=707072&hide_title=true">
</a>

<br>

<a href="https://github.com/adityaanand0001">
  <img height="155" src="https://github-readme-streak-stats.vercel.app?user=adityaanand0001&hide_border=true&background=f5f5f5&stroke=cacacb&ring=111111&fire=d30005&currStreakNum=111111&sideNums=111111&currStreakLabel=707072&sideLabels=707072&dates=9e9ea0">
</a>

<br>

<!-- ─────────────────────────────────────────────────────────────────
TROPHIES
───────────────────────────────────────────────────────────────── -->
<svg width="960" height="48" viewBox="0 0 960 48" xmlns="http://www.w3.org/2000/svg">
  <style>
    .label { font-family: 'Segoe UI','Helvetica Neue',Arial,sans-serif; font-size: 18px; fill: #111111; font-weight: 600; }
    .rule { stroke: #e5e5e5; stroke-width: 1; }
  </style>
  <text x="0" y="24" class="label">TROPHIES</text>
  <line x1="0" y1="44" x2="960" y2="44" class="rule"/>
</svg>

<br>

<a href="https://github.com/adityaanand0001">
  <img src="https://github-profile-trophy.vercel.app/?username=adityaanand0001&theme=flat&no-frame=true&column=7&margin-w=6&title=Commits,PR,Repositories,Stars,Followers,Issues,PullRequest" height="130">
</a>

<br>

<!-- ─────────────────────────────────────────────────────────────────
SNAKE GAME — contribution grid animation
───────────────────────────────────────────────────────────────── -->
<svg width="960" height="48" viewBox="0 0 960 48" xmlns="http://www.w3.org/2000/svg">
  <style>
    .label { font-family: 'Segoe UI','Helvetica Neue',Arial,sans-serif; font-size: 18px; fill: #111111; font-weight: 600; }
    .rule { stroke: #e5e5e5; stroke-width: 1; }
  </style>
  <text x="0" y="24" class="label">CONTRIBUTION GAME</text>
  <line x1="0" y1="44" x2="960" y2="44" class="rule"/>
</svg>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/adityaanand0001/adityaanand0001/output/snake-dark.svg">
  <img src="https://raw.githubusercontent.com/adityaanand0001/adityaanand0001/output/snake.svg" width="800" alt="Snake contribution animation">
</picture>

<br>

<!-- ─────────────────────────────────────────────────────────────────
ABOUT — SVG card with Nike-styled typography
───────────────────────────────────────────────────────────────── -->
<svg width="960" height="48" viewBox="0 0 960 48" xmlns="http://www.w3.org/2000/svg">
  <style>
    .label { font-family: 'Segoe UI','Helvetica Neue',Arial,sans-serif; font-size: 18px; fill: #111111; font-weight: 600; }
    .rule { stroke: #e5e5e5; stroke-width: 1; }
  </style>
  <text x="0" y="24" class="label">ABOUT</text>
  <line x1="0" y1="44" x2="960" y2="44" class="rule"/>
</svg>

<br>

<!-- About text as SVG for Nike typography control -->
<svg width="960" height="130" viewBox="0 0 960 130" xmlns="http://www.w3.org/2000/svg">
  <style>
    .body { font-family: 'Segoe UI','Helvetica Neue',Arial,sans-serif; font-size: 16px; fill: #39393b; line-height: 1.75; }
  </style>
  <text x="0" y="24" class="body">I build software where performance and design are inseparable.</text>
  <text x="0" y="50" class="body">Full-stack web applications, cloud infrastructure, and developer tooling —</text>
  <text x="0" y="76" class="body">with an eye toward systems that feel as good to use as they are to maintain.</text>
  <text x="0" y="108" class="body" fill="#707072" font-size="14">Based in India · Open to collaboration</text>
</svg>

<br>

<!-- ─────────────────────────────────────────────────────────────────
FOOTER — Nike utility-xs legal row
───────────────────────────────────────────────────────────────── -->
<svg width="960" height="36" viewBox="0 0 960 36" xmlns="http://www.w3.org/2000/svg">
  <style>
    .rule { stroke: #cacacb; stroke-width: 1; }
    .text { font-family: 'Segoe UI','Helvetica Neue',Arial,sans-serif; font-size: 10px; fill: #707072; }
  </style>
  <line x1="0" y1="0" x2="960" y2="0" class="rule"/>
  <text x="0" y="22" class="text">&copy; 2026 ADITYA ANAND  ·  BUILT WITH THE NIKE DESIGN SYSTEM</text>
  <text x="960" y="22" class="text" text-anchor="end">INDIA</text>
</svg>

<br>

<img src="https://komarev.com/ghpvc/?username=adityaanand0001&style=flat-square&color=111111&label=VISITORS" alt="Profile views">

</div>
