<div align="center">

<!-- Custom Animated Header SVG -->
<svg width="800" height="200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="headerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#000000"/>
      <stop offset="50%" style="stop-color:#00ff88"/>
      <stop offset="100%" style="stop-color:#000000"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="glitch">
      <feOffset in="SourceGraphic" dx="2" dy="0" result="r"/>
      <feOffset in="SourceGraphic" dx="-2" dy="0" result="b"/>
      <feColorMatrix in="r" type="matrix" values="1 0 0 0 0  0 0 0 0 0  0 0 0 0 0  0 0 0 1 0" result="red"/>
      <feColorMatrix in="b" type="matrix" values="0 0 0 0 0  0 0 0 0 0  0 0 1 0 0  0 0 0 1 0" result="blue"/>
      <feBlend in="red" in2="blue" mode="screen"/>
    </filter>
  </defs>

  <rect width="100%" height="100%" fill="#0d1117"/>

  <!-- Animated scan line -->
  <rect width="100%" height="2" fill="#00ff88" opacity="0.3">
    <animate attributeName="y" from="0" to="200" dur="3s" repeatCount="indefinite"/>
  </rect>

  <!-- Matrix rain effect -->
  <text x="50" y="30" fill="#00ff88" opacity="0.1" font-family="monospace" font-size="12">01001000 01000001 01000011 01001011</text>
  <text x="200" y="50" fill="#00ff88" opacity="0.15" font-family="monospace" font-size="10">10110010 01101001 00110100</text>
  <text x="500" y="40" fill="#00ff88" opacity="0.1" font-family="monospace" font-size="12">01110011 01100101 01100011</text>
  <text x="100" y="180" fill="#00ff88" opacity="0.1" font-family="monospace" font-size="10">00101111 01100100 01100101 01110110</text>
  <text x="600" y="170" fill="#00ff88" opacity="0.15" font-family="monospace" font-size="12">01101110 01110101 01101100 01101100</text>

  <!-- Main title with glow -->
  <text x="400" y="100" text-anchor="middle" font-family="monospace" font-size="72" font-weight="bold" fill="#00ff88" filter="url(#glow)">
    a0x194
    <animate attributeName="opacity" values="1;0.8;1" dur="2s" repeatCount="indefinite"/>
  </text>

  <!-- Subtitle -->
  <text x="400" y="140" text-anchor="middle" font-family="monospace" font-size="16" fill="#ffffff">
    SECURITY RESEARCHER  |  TOOL DEVELOPER  |  BUG HUNTER
  </text>

  <!-- Animated underline -->
  <line x1="150" y1="155" x2="650" y2="155" stroke="#00ff88" stroke-width="1">
    <animate attributeName="stroke-dasharray" values="0,500;500,0" dur="2s" fill="freeze"/>
  </line>

  <!-- Corner decorations -->
  <path d="M0,0 L50,0 L50,5 L5,5 L5,50 L0,50 Z" fill="#00ff88"/>
  <path d="M800,0 L750,0 L750,5 L795,5 L795,50 L800,50 Z" fill="#00ff88"/>
  <path d="M0,200 L50,200 L50,195 L5,195 L5,150 L0,150 Z" fill="#00ff88"/>
  <path d="M800,200 L750,200 L750,195 L795,195 L795,150 L800,150 Z" fill="#00ff88"/>
</svg>

<!-- Typing Effect -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=24&duration=3000&pause=1000&color=00FF88&center=true&vCenter=true&random=false&width=600&height=50&lines=%24+sudo+access+--granted;%24+loading+profile...;%24+status%3A+always+hacking+%F0%9F%94%93" alt="Typing" />

</div>

---

<!-- Terminal Style Info Box -->
<div align="center">

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                              ║
║   ┌──(root㉿a0x194)-[~]                                                      ║
║   └─# whoami                                                                 ║
║                                                                              ║
║   ▀█▀ █▀█ █▄█ █░█ ▄▀█ █▀█ █▀▄ █▀▀ █▀█                                       ║
║   ░█░ █▀▄ ░█░ █▀█ █▀█ █▀▄ █▄▀ ██▄ █▀▄                                       ║
║                                                                              ║
║   ╭─────────────────────────────────────────────────────────────────────╮    ║
║   │  ROLE      →  Security Researcher & Tool Developer                  │    ║
║   │  FOCUS     →  Web Security | Cloud | CI/CD | Red Team               │    ║
║   │  WEBSITE   →  https://www.tryharder.space                           │    ║
║   │  TOOLS     →  https://www.tryharder.space/tools/                    │    ║
║   │  STATUS    →  Building weapons for ethical hackers                  │    ║
║   ╰─────────────────────────────────────────────────────────────────────╯    ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

</div>

---

<!-- Custom SVG Skill Bars -->
<h2 align="center">
<img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width="24">
SKILL_MATRIX.exe
</h2>

<div align="center">

<svg width="600" height="280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="barGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00ff88"/>
      <stop offset="100%" style="stop-color:#00aa55"/>
    </linearGradient>
  </defs>

  <rect width="100%" height="100%" fill="#0d1117" rx="10"/>

  <!-- Go -->
  <text x="30" y="40" fill="#00ff88" font-family="monospace" font-size="14">Go</text>
  <rect x="120" y="25" width="400" height="20" fill="#1a1a2e" rx="3"/>
  <rect x="120" y="25" width="380" height="20" fill="url(#barGrad)" rx="3">
    <animate attributeName="width" from="0" to="380" dur="1s" fill="freeze"/>
  </rect>
  <text x="530" y="40" fill="#ffffff" font-family="monospace" font-size="12">95%</text>

  <!-- Python -->
  <text x="30" y="80" fill="#00ff88" font-family="monospace" font-size="14">Python</text>
  <rect x="120" y="65" width="400" height="20" fill="#1a1a2e" rx="3"/>
  <rect x="120" y="65" width="360" height="20" fill="url(#barGrad)" rx="3">
    <animate attributeName="width" from="0" to="360" dur="1.2s" fill="freeze"/>
  </rect>
  <text x="530" y="80" fill="#ffffff" font-family="monospace" font-size="12">90%</text>

  <!-- JavaScript -->
  <text x="30" y="120" fill="#00ff88" font-family="monospace" font-size="14">JavaScript</text>
  <rect x="120" y="105" width="400" height="20" fill="#1a1a2e" rx="3"/>
  <rect x="120" y="105" width="340" height="20" fill="url(#barGrad)" rx="3">
    <animate attributeName="width" from="0" to="340" dur="1.4s" fill="freeze"/>
  </rect>
  <text x="530" y="120" fill="#ffffff" font-family="monospace" font-size="12">85%</text>

  <!-- Bash -->
  <text x="30" y="160" fill="#00ff88" font-family="monospace" font-size="14">Bash</text>
  <rect x="120" y="145" width="400" height="20" fill="#1a1a2e" rx="3"/>
  <rect x="120" y="145" width="360" height="20" fill="url(#barGrad)" rx="3">
    <animate attributeName="width" from="0" to="360" dur="1.6s" fill="freeze"/>
  </rect>
  <text x="530" y="160" fill="#ffffff" font-family="monospace" font-size="12">90%</text>

  <!-- Web Security -->
  <text x="30" y="200" fill="#ff6b6b" font-family="monospace" font-size="14">Web Security</text>
  <rect x="120" y="185" width="400" height="20" fill="#1a1a2e" rx="3"/>
  <rect x="120" y="185" width="380" height="20" fill="#ff6b6b" rx="3">
    <animate attributeName="width" from="0" to="380" dur="1.8s" fill="freeze"/>
  </rect>
  <text x="530" y="200" fill="#ffffff" font-family="monospace" font-size="12">95%</text>

  <!-- Cloud Security -->
  <text x="30" y="240" fill="#ff6b6b" font-family="monospace" font-size="14">Cloud Sec</text>
  <rect x="120" y="225" width="400" height="20" fill="#1a1a2e" rx="3"/>
  <rect x="120" y="225" width="340" height="20" fill="#ff6b6b" rx="3">
    <animate attributeName="width" from="0" to="340" dur="2s" fill="freeze"/>
  </rect>
  <text x="530" y="240" fill="#ffffff" font-family="monospace" font-size="12">85%</text>

</svg>

</div>

---

<!-- Arsenal Section -->
<h2 align="center">
⚔️ ARSENAL // SECURITY TOOLS
</h2>

<div align="center">
<table>
<tr>
<td align="center" width="25%">

<svg width="150" height="150" xmlns="http://www.w3.org/2000/svg">
  <rect width="100%" height="100%" fill="#0d1117" rx="10"/>
  <circle cx="75" cy="60" r="35" fill="none" stroke="#00ff88" stroke-width="3">
    <animate attributeName="stroke-dasharray" values="0,220;220,0" dur="2s" fill="freeze"/>
  </circle>
  <text x="75" y="65" text-anchor="middle" fill="#00ff88" font-family="monospace" font-size="20" font-weight="bold">CORS</text>
  <text x="75" y="120" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="11">Misconfiguration</text>
  <text x="75" y="135" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="11">Scanner</text>
</svg>

**[CORScan](https://github.com/a0x194/corscan)**

</td>
<td align="center" width="25%">

<svg width="150" height="150" xmlns="http://www.w3.org/2000/svg">
  <rect width="100%" height="100%" fill="#0d1117" rx="10"/>
  <path d="M40,50 L110,50 M40,70 L110,70 M40,90 L80,90" stroke="#ff6b6b" stroke-width="3" fill="none">
    <animate attributeName="stroke-dasharray" values="0,100;100,0" dur="1.5s" fill="freeze"/>
  </path>
  <text x="75" y="120" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="11">HTTP Request</text>
  <text x="75" y="135" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="11">Smuggling</text>
</svg>

**[HTTPSmuggler](https://github.com/a0x194/httpsmuggler)**

</td>
<td align="center" width="25%">

<svg width="150" height="150" xmlns="http://www.w3.org/2000/svg">
  <rect width="100%" height="100%" fill="#0d1117" rx="10"/>
  <ellipse cx="75" cy="55" rx="40" ry="20" fill="none" stroke="#00ff88" stroke-width="2"/>
  <ellipse cx="75" cy="70" rx="40" ry="20" fill="none" stroke="#00ff88" stroke-width="2"/>
  <ellipse cx="75" cy="85" rx="40" ry="20" fill="none" stroke="#00ff88" stroke-width="2"/>
  <text x="75" y="120" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="11">Cloud Bucket</text>
  <text x="75" y="135" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="11">Scanner</text>
</svg>

**[CloudBucket](https://github.com/a0x194/cloudbucket)**

</td>
<td align="center" width="25%">

<svg width="150" height="150" xmlns="http://www.w3.org/2000/svg">
  <rect width="100%" height="100%" fill="#0d1117" rx="10"/>
  <circle cx="55" cy="60" r="15" fill="none" stroke="#ff6b6b" stroke-width="2"/>
  <circle cx="95" cy="60" r="15" fill="none" stroke="#ff6b6b" stroke-width="2"/>
  <line x1="70" y1="60" x2="80" y2="60" stroke="#ff6b6b" stroke-width="2"/>
  <path d="M55,75 L55,95 M95,75 L95,95" stroke="#ff6b6b" stroke-width="2"/>
  <text x="75" y="120" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="11">CI/CD Pipeline</text>
  <text x="75" y="135" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="11">Security</text>
</svg>

**[CICDGuard](https://github.com/a0x194/cicdguard)**

</td>
</tr>
</table>
</div>

---

<!-- Tech Stack Icons -->
<div align="center">
<img src="https://skillicons.dev/icons?i=go,python,js,bash,docker,linux,git,github,aws,gcp,azure,kubernetes&theme=dark&perline=12" />
</div>

---

<!-- Connect Section with Custom SVG -->
<div align="center">

<svg width="700" height="180" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="boxGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="100%" style="stop-color:#161b22"/>
    </linearGradient>
  </defs>

  <rect width="100%" height="100%" fill="url(#boxGrad)" rx="15"/>
  <rect x="2" y="2" width="696" height="176" fill="none" stroke="#00ff88" stroke-width="2" rx="15"/>

  <!-- Title -->
  <text x="350" y="40" text-anchor="middle" fill="#00ff88" font-family="monospace" font-size="20" font-weight="bold">
    [ CONNECT ]
  </text>

  <!-- Links -->
  <text x="350" y="80" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="14">
    🌐  PLATFORM  →  https://www.tryharder.space
  </text>

  <text x="350" y="110" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="14">
    🔧  TOOLS     →  https://www.tryharder.space/tools/
  </text>

  <text x="350" y="140" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="14">
    📧  CONTACT   →  admin@tryharder.space
  </text>

  <!-- Animated corner -->
  <rect x="10" y="10" width="30" height="3" fill="#00ff88">
    <animate attributeName="width" values="30;50;30" dur="2s" repeatCount="indefinite"/>
  </rect>
  <rect x="10" y="10" width="3" height="30" fill="#00ff88">
    <animate attributeName="height" values="30;50;30" dur="2s" repeatCount="indefinite"/>
  </rect>

  <rect x="660" y="167" width="30" height="3" fill="#00ff88">
    <animate attributeName="x" values="660;640;660" dur="2s" repeatCount="indefinite"/>
  </rect>
  <rect x="687" y="140" width="3" height="30" fill="#00ff88">
    <animate attributeName="y" values="140;120;140" dur="2s" repeatCount="indefinite"/>
  </rect>
</svg>

</div>

---

<!-- Animated Footer -->
<div align="center">

<svg width="800" height="100" xmlns="http://www.w3.org/2000/svg">
  <rect width="100%" height="100%" fill="#0d1117"/>

  <!-- Animated line -->
  <line x1="0" y1="20" x2="800" y2="20" stroke="#00ff88" stroke-width="1" stroke-dasharray="5,5">
    <animate attributeName="stroke-dashoffset" values="0;-10" dur="0.5s" repeatCount="indefinite"/>
  </line>

  <!-- Quote -->
  <text x="400" y="55" text-anchor="middle" fill="#00ff88" font-family="monospace" font-size="14" opacity="0.8">
    "The quieter you become, the more you are able to hear."
  </text>

  <text x="400" y="80" text-anchor="middle" fill="#666666" font-family="monospace" font-size="12">
    ━━━━━━━━━━━━━━━  TryHarder Security  ━━━━━━━━━━━━━━━
  </text>

  <!-- Animated line bottom -->
  <line x1="0" y1="95" x2="800" y2="95" stroke="#00ff88" stroke-width="1" stroke-dasharray="5,5">
    <animate attributeName="stroke-dashoffset" values="-10;0" dur="0.5s" repeatCount="indefinite"/>
  </line>
</svg>

</div>

<div align="center">
<img src="https://komarev.com/ghpvc/?username=a0x194&color=00ff88&style=for-the-badge&label=VISITORS"/>
</div>
