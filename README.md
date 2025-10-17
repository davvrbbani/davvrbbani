## Hi there 👋

<!--
**davvrbbani/davvrbbani** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<svg xmlns="http://www.w3.org/2000/svg" width="800" height="400">
  <defs>
    <!-- Gradasi background -->
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#000000"/>
      <stop offset="50%" stop-color="#001a00"/>
      <stop offset="100%" stop-color="#002b00"/>
    </linearGradient>

    <!-- Efek refleksi bawah teks -->
    <linearGradient id="reflection" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="rgba(0,255,100,0.4)"/>
      <stop offset="100%" stop-color="transparent"/>
    </linearGradient>

    <style>
      .bg {
        fill: url(#bg);
      }

      /* Teks utama */
      .text {
        font-family: 'Courier New', monospace;
        font-size: 80px;
        font-weight: bold;
        text-anchor: middle;
        dominant-baseline: middle;
        fill: #00cc55;
        opacity: 0.85;
        filter: drop-shadow(0 0 10px #009933)
                drop-shadow(0 0 20px rgba(0,255,0,0.2));
      }

      /* Refleksi bawah teks */
      .reflection {
        font-family: 'Courier New', monospace;
        font-size: 80px;
        font-weight: bold;
        text-anchor: middle;
        dominant-baseline: middle;
        fill: url(#reflection);
        transform: scaleY(-1);
        opacity: 0.3;
      }

      /* Garis scan tipis */
      .scanline {
        fill: none;
        stroke: rgba(0,255,0,0.06);
        stroke-width: 1;
      }

      /* Animasi glitch */
      @keyframes glitch {
        0%, 100% { transform: translate(0, 0); }
        20% { transform: translate(-1px, 1px); }
        40% { transform: translate(1px, -1px); }
        60% { transform: translate(-1px, -1px); }
        80% { transform: translate(1px, 1px); }
      }

      .glitch {
        animation: glitch 0.3s infinite;
      }
    </style>
  </defs>

  <!-- Background -->
  <rect class="bg" width="800" height="400"/>

  <!-- Efek glitch (lapisan teks berwarna berbeda) -->
  <text x="400" y="220" class="text glitch" fill="#00ff66" opacity="0.2">DAVVRBBANI</text>
  <text x="403" y="223" class="text glitch" fill="#009944" opacity="0.6">DAVVRBBANI</text>

  <!-- Teks utama -->
  <text x="400" y="220" class="text glitch">DAVVRBBANI</text>

  <!-- Refleksi di bawah teks -->
  <text x="400" y="270" class="reflection">DAVVRBBANI</text>

  <!-- Garis scan CRT -->
  <g>
    <line x1="0" y1="50" x2="800" y2="50" class="scanline"/>
    <line x1="0" y1="100" x2="800" y2="100" class="scanline"/>
    <line x1="0" y1="150" x2="800" y2="150" class="scanline"/>
    <line x1="0" y1="200" x2="800" y2="200" class="scanline"/>
    <line x1="0" y1="250" x2="800" y2="250" class="scanline"/>
    <line x1="0" y1="300" x2="800" y2="300" class="scanline"/>
    <line x1="0" y1="350" x2="800" y2="350" class="scanline"/>
  </g>
</svg>


