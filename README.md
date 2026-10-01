<div align="center">

<svg width="600" height="200" xmlns="http://www.w3.org/2000/svg">
  <!-- 背景 -->
  <rect width="600" height="200" fill="#0a0a0a"/>
  
  <!-- 扫描线效果 -->
  <defs>
    <pattern id="scanlines" patternUnits="userSpaceOnUse" width="100%" height="4">
      <rect width="100%" height="2" fill="white" opacity="0.03"/>
    </pattern>
    <linearGradient id="glow" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00ff41;stop-opacity:0.3"/>
      <stop offset="50%" style="stop-color:#00ff41;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#00ff41;stop-opacity:0.3"/>
    </linearGradient>
    <filter id="glowFilter">
      <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="glitch">
      <feTurbulence type="turbulence" baseFrequency="0.02" numOctaves="3" result="noise">
        <animate attributeName="baseFrequency" values="0.02;0.05;0.02;0.03;0.02" dur="0.2s" repeatCount="indefinite" begin="2s"/>
      </feTurbulence>
      <feDisplacementMap in="SourceGraphic" in2="noise" scale="0" xChannelSelector="R" yChannelSelector="G">
        <animate attributeName="scale" values="0;8;0;5;0" dur="0.2s" repeatCount="indefinite" begin="2s"/>
      </feDisplacementMap>
    </filter>
  </defs>
  
  <rect width="600" height="200" fill="url(#scanlines)"/>
  
  <!-- 装饰性代码雨 -->
  <g fill="#00ff41" opacity="0.15" font-family="monospace" font-size="10">
    <text x="50" y="30">01001000</text>
    <text x="520" y="50">10110101</text>
    <text x="80" y="170">0xF02A</text>
    <text x="480" y="180">$ echo hello</text>
    <text x="30" y="90">root@void:~#</text>
    <text x="500" y="120">[ OK ]</text>
    <text x="150" y="20">///</text>
    <text x="400" y="160">null</text>
  </g>
  
  <!-- 主文字：hello -->
  <g filter="url(#glowFilter)" font-family="'Courier New', monospace" font-weight="bold">
    <!-- 第一层：绿色主体 -->
    <text x="300" y="115" text-anchor="middle" font-size="72" fill="url(#glow)">
      h
      <animate attributeName="opacity" values="0;1" dur="0.1s" fill="freeze" begin="0.3s"/>
    </text>
    <text x="300" y="115" text-anchor="middle" font-size="72" fill="url(#glow)">
      he
      <animate attributeName="opacity" values="0;1" dur="0.1s" fill="freeze" begin="0.5s"/>
    </text>
    <text x="300" y="115" text-anchor="middle" font-size="72" fill="url(#glow)">
      hel
      <animate attributeName="opacity" values="0;1" dur="0.1s" fill="freeze" begin="0.7s"/>
    </text>
    <text x="300" y="115" text-anchor="middle" font-size="72" fill="url(#glow)">
      hell
      <animate attributeName="opacity" values="0;1" dur="0.1s" fill="freeze" begin="0.9s"/>
    </text>
    <text x="300" y="115" text-anchor="middle" font-size="72" fill="url(#glow)">
      hello
      <animate attributeName="opacity" values="0;1" dur="0.1s" fill="freeze" begin="1.1s"/>
    </text>
    
    <!-- 最终显示的 hello -->
    <text x="300" y="115" text-anchor="middle" font-size="72" fill="#00ff41" opacity="0">
      hello
      <animate attributeName="opacity" values="0;1" dur="0.1s" fill="freeze" begin="1.2s"/>
      <animate attributeName="opacity" values="1;0.8;1;0.9;1" dur="0.15s" fill="freeze" begin="2s"/>
    </text>
    
    <!-- Glitch 层（红色偏移）-->
    <text x="298" y="113" text-anchor="middle" font-size="72" fill="#ff0040" opacity="0">
      hello
      <animate attributeName="opacity" values="0;0;0.5;0;0.3;0" dur="0.3s" repeatCount="indefinite" begin="2.5s"/>
    </text>
    <!-- Glitch 层（青色偏移）-->
    <text x="302" y="117" text-anchor="middle" font-size="72" fill="#00fff0" opacity="0">
      hello
      <animate attributeName="opacity" values="0;0;0.4;0;0.2;0" dur="0.3s" repeatCount="indefinite" begin="2.5s"/>
    </text>
  </g>
  
  <!-- 闪烁光标 -->
  <rect x="385" y="75" width="8" height="55" fill="#00ff41" filter="url(#glowFilter)">
    <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite" begin="1.3s"/>
  </rect>
  
  <!-- 底部状态行 -->
  <g font-family="'Courier New', monospace" font-size="11" fill="#00ff41" opacity="0.6">
    <text x="20" y="190">
      <tspan>SYSTEM</tspan>
      <tspan fill="#00ff41" opacity="0.3"> · </tspan>
      <tspan>CONNECTED</tspan>
    </text>
    <text x="580" y="190" text-anchor="end">
      <tspan>v1.0.0</tspan>
    </text>
    <text x="300" y="190" text-anchor="middle" opacity="0.4">
      <tspan>_</tspan>
      <animate attributeName="opacity" values="0.4;0.1;0.4" dur="2s" repeatCount="indefinite"/>
    </text>
  </g>
</svg>

</div>
