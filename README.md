# 🌴 hello！

<div align="center">

<i>「I like to move it, move it\~」</i>

<br />

<svg width="800" height="380" xmlns="http://www.w3.org/2000/svg">
  <!-- 天空 -->
  <defs>
    <linearGradient id="skyGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#4FC3F7"/>
      <stop offset="60%" style="stop-color:#81D4FA"/>
      <stop offset="100%" style="stop-color:#B3E5FC"/>
    </linearGradient>
    <linearGradient id="sandGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#FFE082"/>
      <stop offset="100%" style="stop-color:#FFD54F"/>
    </linearGradient>
  </defs>

  <rect width="800" height="280" fill="url(#skyGrad)"/>

  <!-- 远山 -->

  <path d="M0 200 L150 120 L280 180 L420 100 L580 170 L720 130 L800 190 L800 280 L0 280 Z" fill="#90CAF9" opacity="0.4"/>
  <path d="M0 230 L100 170 L250 210 L400 150 L550 200 L700 160 L800 220 L800 280 L0 280 Z" fill="#64B5F6" opacity="0.3"/>

  <!-- 太阳 -->

  <circle cx="680" cy="80" r="40" fill="#FFD54F">
    <animate attributeName="r" values="40;43;40" dur="3s" repeatCount="indefinite"/>
  </circle>
  <g stroke="#FFD54F" stroke-width="3" stroke-linecap="round">
    <line x1="680" y1="25" x2="680" y2="10">
      <animate attributeName="y1" values="25;22;25" dur="3s" repeatCount="indefinite"/>
    </line>
    <line x1="680" y1="135" x2="680" y2="150">
      <animate attributeName="y2" values="150;153;150" dur="3s" repeatCount="indefinite"/>
    </line>
    <line x1="625" y1="80" x2="610" y2="80">
      <animate attributeName="x2" values="610;607;610" dur="3s" repeatCount="indefinite"/>
    </line>
    <line x1="735" y1="80" x2="750" y2="80">
      <animate attributeName="x1" values="735;738;735" dur="3s" repeatCount="indefinite"/>
    </line>
  </g>

  <!-- 云朵 -->

  <g fill="white" opacity="0.85">
    <g>
      <ellipse cx="100" cy="60" rx="30" ry="15"/>
      <ellipse cx="125" cy="55" rx="25" ry="13"/>
      <ellipse cx="80" cy="62" rx="20" ry="11"/>
      <animateTransform attributeName="transform" type="translate"
        from="-100 0" to="900 0" dur="60s" repeatCount="indefinite"/>
    </g>
    <g>
      <ellipse cx="450" cy="40" rx="25" ry="12"/>
      <ellipse cx="470" cy="36" rx="20" ry="10"/>
      <animateTransform attributeName="transform" type="translate"
        from="-200 0" to="800 0" dur="80s" repeatCount="indefinite"/>
    </g>
  </g>

  <!-- 沙地 -->

  <path d="M0 280 Q200 260 400 275 Q600 290 800 270 L800 380 L0 380 Z" fill="url(#sandGrad)"/>

  <!-- 棕榈树 1 -->

  <g transform="translate(50, 180)">
    <rect x="-5" y="40" width="10" height="70" fill="#8D6E63" rx="3"/>
    <path d="M0 40 Q-30 20 -50 35" stroke="#5D4037" stroke-width="1" fill="none"/>
    <path d="M0 60 Q-20 50 -35 60" stroke="#5D4037" stroke-width="1" fill="none"/>
    <!-- 树叶 -->
    <path d="M0 40 Q-40 10 -60 30 Q-30 25 0 45 Z" fill="#2E7D32">
      <animateTransform attributeName="transform" type="rotate" values="0 0 40; -3 0 40; 0 0 40" dur="4s" repeatCount="indefinite"/>
    </path>
    <path d="M0 40 Q40 10 60 30 Q30 25 0 45 Z" fill="#388E3C">
      <animateTransform attributeName="transform" type="rotate" values="0 0 40; 3 0 40; 0 0 40" dur="4s" repeatCount="indefinite"/>
    </path>
    <path d="M0 40 Q-20 -5 -10 -20 Q5 0 5 45 Z" fill="#43A047">
      <animateTransform attributeName="transform" type="rotate" values="0 0 40; -2 0 40; 0 0 40" dur="3.5s" repeatCount="indefinite"/>
    </path>
    <path d="M0 40 Q25 -10 15 -25 Q0 0 -5 45 Z" fill="#4CAF50">
      <animateTransform attributeName="transform" type="rotate" values="0 0 40; 2 0 40; 0 0 40" dur="3.5s" repeatCount="indefinite"/>
    </path>
    <!-- 椰子 -->
    <circle cx="-8" cy="48" r="4" fill="#5D4037"/>
    <circle cx="6" cy="50" r="3" fill="#5D4037"/>
  </g>

  <!-- 棕榈树 2 -->

  <g transform="translate(730, 190)">
    <rect x="-4" y="30" width="8" height="60" fill="#8D6E63" rx="3"/>
    <path d="M-4 60 Q-18 52 -30 58" stroke="#5D4037" stroke-width="1" fill="none"/>
    <path d="M0 35 Q-35 10 -50 28 Q-25 22 0 40 Z" fill="#388E3C">
      <animateTransform attributeName="transform" type="rotate" values="0 0 35; 3 0 35; 0 0 35" dur="4.5s" repeatCount="indefinite"/>
    </path>
    <path d="M0 35 Q35 10 55 28 Q25 22 0 40 Z" fill="#43A047">
      <animateTransform attributeName="transform" type="rotate" values="0 0 35; -3 0 35; 0 0 35" dur="4.5s" repeatCount="indefinite"/>
    </path>
    <path d="M0 35 Q-15 -10 -5 -25 Q5 -5 5 40 Z" fill="#4CAF50">
      <animateTransform attributeName="transform" type="rotate" values="0 0 35; 2 0 35; 0 0 35" dur="4s" repeatCount="indefinite"/>
    </path>
    <path d="M0 35 Q20 -10 10 -25 Q-5 -5 -5 40 Z" fill="#66BB6A">
      <animateTransform attributeName="transform" type="rotate" values="0 0 35; -2 0 35; 0 0 35" dur="4s" repeatCount="indefinite"/>
    </path>
    <circle cx="5" cy="42" r="3" fill="#5D4037"/>
  </g>

  <!-- 小草 -->

  <g fill="#7CB342">
    <path d="M100 290 Q102 280 105 290 Z"/>
    <path d="M110 292 Q113 282 116 292 Z"/>
    <path d="M120 288 Q122 278 125 288 Z"/>
    <path d="M600 295 Q603 285 606 295 Z"/>
    <path d="M620 290 Q622 280 625 290 Z"/>
    <path d="M350 298 Q352 288 355 298 Z"/>
    <path d="M360 295 Q362 285 365 295 Z"/>
  </g>

  <!-- ==================== 长颈鹿 Melman 🦒 ==================== -->

  <g transform="translate(100, 170)">
    <!-- 腿 -->
    <rect x="-18" y="70" width="6" height="40" rx="2" fill="#FFB74D"/>
    <rect x="-6" y="72" width="6" height="38" rx="2" fill="#FFA726"/>
    <rect x="8" y="70" width="6" height="40" rx="2" fill="#FFB74D"/>
    <rect x="20" y="72" width="6" height="38" rx="2" fill="#FFA726"/>
    <!-- 脚 -->
    <ellipse cx="-15" cy="112" rx="5" ry="3" fill="#5D4037"/>
    <ellipse cx="-3" cy="112" rx="5" ry="3" fill="#5D4037"/>
    <ellipse cx="11" cy="112" rx="5" ry="3" fill="#5D4037"/>
    <ellipse cx="23" cy="112" rx="5" ry="3" fill="#5D4037"/>
    <!-- 身体 -->
    <ellipse cx="5" cy="55" rx="28" ry="20" fill="#FFB74D"/>
    <!-- 身上的斑点 -->
    <circle cx="-10" cy="48" r="4" fill="#E65100" opacity="0.5"/>
    <circle cx="5" cy="45" r="3.5" fill="#E65100" opacity="0.5"/>
    <circle cx="20" cy="50" r="4" fill="#E65100" opacity="0.5"/>
    <circle cx="-5" cy="60" r="3" fill="#E65100" opacity="0.5"/>
    <circle cx="15" cy="62" r="3.5" fill="#E65100" opacity="0.5"/>
    <!-- 长脖子 -->
    <rect x="-5" y="5" width="12" height="55" rx="6" fill="#FFB74D"/>
    <!-- 脖子上的斑点 -->
    <circle cx="1" cy="15" r="3" fill="#E65100" opacity="0.5"/>
    <circle cx="3" cy="30" r="2.5" fill="#E65100" opacity="0.5"/>
    <circle cx="-1" cy="45" r="3" fill="#E65100" opacity="0.5"/>
    <!-- 尾巴 -->
    <path d="M30 50 Q40 45 38 35" stroke="#FFA726" stroke-width="4" fill="none" stroke-linecap="round">
      <animate attributeName="d" values="M30 50 Q40 45 38 35;M30 50 Q42 42 40 32;M30 50 Q40 45 38 35" dur="2s" repeatCount="indefinite"/>
    </path>
    <circle cx="38" cy="33" r="4" fill="#6D4C41"/>
    <!-- 头 -->
    <ellipse cx="0" cy="0" rx="15" ry="12" fill="#FFB74D"/>
    <!-- 角 -->
    <ellipse cx="-6" cy="-14" rx="3" ry="7" fill="#8D6E63"/>
    <ellipse cx="6" cy="-14" rx="3" ry="7" fill="#8D6E63"/>
    <circle cx="-6" cy="-20" r="3.5" fill="#6D4C41"/>
    <circle cx="6" cy="-20" r="3.5" fill="#6D4C41"/>
    <!-- 耳朵 -->
    <ellipse cx="-13" cy="-3" rx="5" ry="7" fill="#FFB74D" transform="rotate(-20 -13 -3)"/>
    <ellipse cx="13" cy="-3" rx="5" ry="7" fill="#FFB74D" transform="rotate(20 13 -3)"/>
    <ellipse cx="-12" cy="-1" rx="3" ry="4" fill="#FFCC80" transform="rotate(-20 -12 -1)"/>
    <ellipse cx="12" cy="-1" rx="3" ry="4" fill="#FFCC80" transform="rotate(20 12 -1)"/>
    <!-- 脸 -->
    <ellipse cx="0" cy="3" rx="10" ry="8" fill="#FFF3E0"/>
    <!-- 眼睛 -->
    <ellipse cx="-5" cy="-1" rx="3.5" ry="4" fill="white"/>
    <ellipse cx="5" cy="-1" rx="3.5" ry="4" fill="white"/>
    <circle cx="-5" cy="0" r="2" fill="#333">
      <animate attributeName="cy" values="0;1;0" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="5" cy="0" r="2" fill="#333">
      <animate attributeName="cy" values="0;1;0" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="-4.5" cy="-0.5" r="0.8" fill="white"/>
    <circle cx="5.5" cy="-0.5" r="0.8" fill="white"/>
    <!-- 鼻子 -->
    <ellipse cx="0" cy="8" rx="4" ry="3" fill="#5D4037"/>
    <circle cx="-1.5" cy="8" r="0.8" fill="#3E2723"/>
    <circle cx="1.5" cy="8" r="0.8" fill="#3E2723"/>
    <!-- 嘴 -->
    <path d="M-4 11 Q0 14 4 11" stroke="#5D4037" stroke-width="1.2" fill="none"/>
    <!-- 脖子上下微动 -->
    <animateTransform attributeName="transform" type="translate"
      values="0,0; 0,-3; 0,0; 0,-2; 0,0" dur="4s" repeatCount="indefinite"/>
  </g>

  <!-- ==================== 狮子 Alex 🦁 ==================== -->

  <g transform="translate(290, 220)">
    <!-- 腿 -->
    <ellipse cx="-20" cy="45" rx="6" ry="10" fill="#FFA726"/>
    <ellipse cx="-8" cy="47" rx="6" ry="9" fill="#FFB74D"/>
    <ellipse cx="8" cy="45" rx="6" ry="10" fill="#FFA726"/>
    <ellipse cx="20" cy="47" rx="6" ry="9" fill="#FFB74D"/>
    <!-- 身体 -->
    <ellipse cx="0" cy="30" rx="32" ry="22" fill="#FFB74D"/>
    <!-- 肚子 -->
    <ellipse cx="0" cy="35" rx="22" ry="14" fill="#FFE0B2"/>
    <!-- 头 -->
    <circle cx="-28" cy="15" r="20" fill="#FFA726"/>
    <!-- 鬃毛 -->
    <g fill="#E65100" opacity="0.8">
      <circle cx="-45" cy="10" r="10"/>
      <circle cx="-48" cy="20" r="8"/>
      <circle cx="-42" cy="28" r="7"/>
      <circle cx="-35" cy="30" r="6"/>
      <circle cx="-20" cy="30" r="7"/>
      <circle cx="-10" cy="25" r="9"/>
      <circle cx="-8" cy="12" r="10"/>
      <circle cx="-12" cy="2" r="8"/>
      <circle cx="-25" cy="-5" r="9"/>
      <circle cx="-38" cy="-2" r="8"/>
      <circle cx="-45" cy="5" r="9"/>
    </g>
    <!-- 耳朵 -->
    <circle cx="-42" cy="5" r="5" fill="#FFA726"/>
    <circle cx="-42" cy="5" r="3" fill="#FFCC80"/>
    <!-- 脸 -->
    <ellipse cx="-28" cy="18" rx="14" ry="12" fill="#FFE0B2"/>
    <!-- 眼睛 -->
    <ellipse cx="-34" cy="12" r="4" ry="4.5" fill="white"/>
    <ellipse cx="-22" cy="12" r="4" ry="4.5" fill="white"/>
    <circle cx="-34" cy="13" r="2.5" fill="#333">
      <animate attributeName="cy" values="13;14.5;13" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="-22" cy="13" r="2.5" fill="#333">
      <animate attributeName="cy" values="13;14.5;13" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="-33" cy="12" r="1" fill="white"/>
    <circle cx="-21" cy="12" r="1" fill="white"/>
    <!-- 鼻子 -->
    <ellipse cx="-28" cy="20" rx="3.5" ry="2.5" fill="#5D4037"/>
    <!-- 嘴 -->
    <path d="M-33 24 Q-28 28 -23 24" stroke="#5D4037" stroke-width="1.5" fill="none"/>
    <path d="M-28 22 L-28 26" stroke="#5D4037" stroke-width="1"/>
    <!-- 胡须 -->
    <line x1="-40" y1="20" x2="-48" y2="18" stroke="#5D4037" stroke-width="0.8"/>
    <line x1="-40" y1="23" x2="-48" y2="23" stroke="#5D4037" stroke-width="0.8"/>
    <line x1="-16" y1="20" x2="-8" y2="18" stroke="#5D4037" stroke-width="0.8"/>
    <line x1="-16" y1="23" x2="-8" y2="23" stroke="#5D4037" stroke-width="0.8"/>
    <!-- 尾巴 -->
    <path d="M32 25 Q48 15 45 0" stroke="#FFA726" stroke-width="5" fill="none" stroke-linecap="round">
      <animate attributeName="d" values="M32 25 Q48 15 45 0;M32 25 Q52 12 48 -3;M32 25 Q48 15 45 0" dur="1.5s" repeatCount="indefinite"/>
    </path>
    <circle cx="45" cy="-2" r="6" fill="#6D4C41"/>
    <!-- 走路摇摆 -->
    <animateTransform attributeName="transform" type="translate"
      values="0,0; 3,-2; 0,0; -3,-2; 0,0" dur="2.5s" repeatCount="indefinite"/>
  </g>

  <!-- ==================== 斑马 Marty 🦓 ==================== -->

  <g transform="translate(470, 230)">
    <!-- 腿 -->
    <rect x="-20" y="35" width="7" height="35" rx="3" fill="white"/>
    <rect x="-8" y="37" width="7" height="33" rx="3" fill="#333"/>
    <rect x="5" y="35" width="7" height="35" rx="3" fill="white"/>
    <rect x="17" y="37" width="7" height="33" rx="3" fill="#333"/>
    <!-- 蹄子 -->
    <ellipse cx="-16" cy="72" rx="5" ry="3" fill="#212121"/>
    <ellipse cx="-4" cy="72" rx="5" ry="3" fill="#212121"/>
    <ellipse cx="9" cy="72" rx="5" ry="3" fill="#212121"/>
    <ellipse cx="21" cy="72" rx="5" ry="3" fill="#212121"/>
    <!-- 身体（白+黑条纹） -->
    <ellipse cx="0" cy="20" rx="35" ry="22" fill="white"/>
    <!-- 条纹 -->
    <path d="M-25 5 Q-20 20 -22 40" stroke="#333" stroke-width="4" fill="none"/>
    <path d="M-12 0 Q-8 18 -10 40" stroke="#333" stroke-width="4" fill="none"/>
    <path d="M2 2 Q5 20 2 40" stroke="#333" stroke-width="4" fill="none"/>
    <path d="M15 5 Q18 22 15 40" stroke="#333" stroke-width="4" fill="none"/>
    <path d="M27 10 Q30 25 27 38" stroke="#333" stroke-width="4" fill="none"/>
    <!-- 肚子 -->
    <ellipse cx="0" cy="28" rx="25" ry="12" fill="#FAFAFA" opacity="0.6"/>
    <!-- 脖子 -->
    <rect x="-10" y="-15" width="14" height="30" rx="7" fill="white"/>
    <path d="M-8 -10 Q-5 0 -7 15" stroke="#333" stroke-width="3" fill="none"/>
    <path d="M2 -12 Q5 0 2 12" stroke="#333" stroke-width="3" fill="none"/>
    <!-- 头 -->
    <ellipse cx="-5" cy="-22" rx="16" ry="13" fill="white"/>
    <!-- 头上的条纹 -->
    <path d="M-18 -28 Q-15 -22 -18 -16" stroke="#333" stroke-width="3" fill="none"/>
    <path d="M-10 -30 Q-7 -22 -10 -14" stroke="#333" stroke-width="3" fill="none"/>
    <path d="M0 -28 Q3 -22 0 -16" stroke="#333" stroke-width="3" fill="none"/>
    <!-- 耳朵 -->
    <ellipse cx="-18" cy="-30" rx="5" ry="8" fill="white" transform="rotate(-15 -18 -30)"/>
    <ellipse cx="6" cy="-30" rx="5" ry="8" fill="white" transform="rotate(15 6 -30)"/>
    <ellipse cx="-17" cy="-28" rx="2.5" ry="5" fill="#BDBDBD" transform="rotate(-15 -17 -28)"/>
    <ellipse cx="7" cy="-28" rx="2.5" ry="5" fill="#BDBDBD" transform="rotate(15 7 -28)"/>
    <!-- 鬃毛 -->
    <path d="M-2 -35 L-5 -42 L1 -40 L4 -44 L7 -40 L10 -42 L8 -35" fill="#333" stroke="#333" stroke-width="1" stroke-linejoin="round">
      <animateTransform attributeName="transform" type="rotate" values="0 3 -35; -2 3 -35; 0 3 -35; 2 3 -35; 0 3 -35" dur="1.5s" repeatCount="indefinite"/>
    </path>
    <!-- 脸 -->
    <ellipse cx="-5" cy="-18" rx="11" ry="9" fill="white"/>
    <!-- 眼睛 -->
    <ellipse cx="-10" cy="-22" r="3.5" ry="4" fill="white"/>
    <ellipse cx="0" cy="-22" r="3.5" ry="4" fill="white"/>
    <circle cx="-10" cy="-21" r="2" fill="#333">
      <animate attributeName="cy" values="-21;-20;-21" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="0" cy="-21" r="2" fill="#333">
      <animate attributeName="cy" values="-21;-20;-21" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="-9" cy="-22" r="0.8" fill="white"/>
    <circle cx="1" cy="-22" r="0.8" fill="white"/>
    <!-- 鼻子 -->
    <ellipse cx="-5" cy="-14" rx="4" ry="2.5" fill="#333"/>
    <!-- 嘴 -->
    <path d="M-10 -11 Q-5 -8 0 -11" stroke="#333" stroke-width="1.2" fill="none"/>
    <!-- 尾巴 -->
    <path d="M35 15 Q50 10 48 -5" stroke="white" stroke-width="5" fill="none" stroke-linecap="round">
      <animate attributeName="d" values="M35 15 Q50 10 48 -5;M35 15 Q55 6 53 -8;M35 15 Q50 10 48 -5" dur="1.8s" repeatCount="indefinite"/>
    </path>
    <circle cx="48" cy="-7" r="4" fill="#333"/>
    <!-- 蹦蹦跳跳 -->
    <animateTransform attributeName="transform" type="translate"
      values="0,0; 0,-6; 0,0; 0,-3; 0,0" dur="1.5s" repeatCount="indefinite"/>
  </g>

  <!-- ==================== 河马 Gloria 🦛 ==================== -->

  <g transform="translate(660, 245)">
    <!-- 腿 -->
    <ellipse cx="-22" cy="35" rx="8" ry="12" fill="#7E57C2"/>
    <ellipse cx="-8" cy="37" rx="8" ry="11" fill="#9575CD"/>
    <ellipse cx="8" cy="35" rx="8" ry="12" fill="#7E57C2"/>
    <ellipse cx="22" cy="37" rx="8" ry="11" fill="#9575CD"/>
    <!-- 脚趾 -->
    <ellipse cx="-26" cy="47" r="3" fill="#5E35B1"/>
    <ellipse cx="-20" cy="47" r="3" fill="#5E35B1"/>
    <ellipse cx="26" cy="47" r="3" fill="#5E35B1"/>
    <ellipse cx="20" cy="47" r="3" fill="#5E35B1"/>
    <!-- 身体 -->
    <ellipse cx="0" cy="15" rx="40" ry="28" fill="#9575CD"/>
    <!-- 肚子 -->
    <ellipse cx="0" cy="22" rx="30" ry="18" fill="#B39DDB"/>
    <!-- 头 -->
    <ellipse cx="0" cy="-15" rx="28" ry="22" fill="#9575CD"/>
    <!-- 耳朵 -->
    <ellipse cx="-22" cy="-28" rx="7" ry="9" fill="#7E57C2" transform="rotate(-20 -22 -28)"/>
    <ellipse cx="22" cy="-28" rx="7" ry="9" fill="#7E57C2" transform="rotate(20 22 -28)"/>
    <ellipse cx="-21" cy="-26" rx="4" ry="5.5" fill="#B39DDB" transform="rotate(-20 -21 -26)"/>
    <ellipse cx="21" cy="-26" rx="4" ry="5.5" fill="#B39DDB" transform="rotate(20 21 -26)"/>
    <!-- 眼睛 -->
    <ellipse cx="-10" cy="-22" rx="6" ry="7" fill="white"/>
    <ellipse cx="10" cy="-22" rx="6" ry="7" fill="white"/>
    <circle cx="-10" cy="-21" r="3.5" fill="#333">
      <animate attributeName="cy" values="-21;-20;-21" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="10" cy="-21" r="3.5" fill="#333">
      <animate attributeName="cy" values="-21;-20;-21" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="-8.5" cy="-22" r="1.2" fill="white"/>
    <circle cx="11.5" cy="-22" r="1.2" fill="white"/>
    <!-- 腮红 -->
    <ellipse cx="-18" cy="-10" rx="5" ry="3" fill="#F48FB1" opacity="0.4"/>
    <ellipse cx="18" cy="-10" rx="5" ry="3" fill="#F48FB1" opacity="0.4"/>
    <!-- 大鼻孔 -->
    <ellipse cx="-6" cy="-5" rx="4" ry="3" fill="#5E35B1"/>
    <ellipse cx="6" cy="-5" rx="4" ry="3" fill="#5E35B1"/>
    <circle cx="-6" cy="-5" r="1.5" fill="#311B92"/>
    <circle cx="6" cy="-5" r="1.5" fill="#311B92"/>
    <!-- 嘴（微笑） -->
    <path d="M-10 3 Q0 10 10 3" stroke="#5E35B1" stroke-width="2" fill="none" stroke-linecap="round"/>
    <path d="M-6 5 Q0 8 6 5" fill="#F48FB1" opacity="0.5"/>
    <!-- 牙齿 -->
    <rect x="-2" y="4" width="2" height="3" fill="white" rx="0.5"/>
    <rect x="1" y="4" width="2" height="3" fill="white" rx="0.5"/>
    <!-- 尾巴 -->
    <path d="M40 15 Q50 12 48 5" stroke="#7E57C2" stroke-width="5" fill="none" stroke-linecap="round">
      <animate attributeName="d" values="M40 15 Q50 12 48 5;M40 15 Q53 9 51 2;M40 15 Q50 12 48 5" dur="2.5s" repeatCount="indefinite"/>
    </path>
    <!-- 呼吸起伏 -->
    <animateTransform attributeName="transform" type="scale"
      values="1 1; 1.01 0.99; 1 1; 0.99 1.01; 1 1" dur="3s" repeatCount="indefinite" additive="sum"/>
    <animateTransform attributeName="transform" type="translate"
      values="0,0; 0,1; 0,0; 0,-1; 0,0" dur="3s" repeatCount="indefinite" additive="sum"/>
  </g>

  <!-- 小鸟 -->

  <g transform="translate(380, 80)">
    <path d="M0 0 Q-8 -5 -12 0 Q-8 2 0 2 Q8 2 12 0 Q8 -5 0 0 Z" fill="#FF7043">
      <animate attributeName="d" values="M0 0 Q-8 -5 -12 0 Q-8 2 0 2 Q8 2 12 0 Q8 -5 0 0 Z;M0 0 Q-8 -8 -12 0 Q-8 3 0 3 Q8 3 12 0 Q8 -8 0 0 Z;M0 0 Q-8 -5 -12 0 Q-8 2 0 2 Q8 2 12 0 Q8 -5 0 0 Z" dur="0.6s" repeatCount="indefinite"/>
    </path>
    <circle cx="6" cy="-1" r="1" fill="#333"/>
    <path d="M12 0 L18 -2 L18 2 Z" fill="#FFA726"/>
    <animateTransform attributeName="transform" type="translate"
      values="0,0; 30,-15; 60,0; 30,10; 0,0" dur="8s" repeatCount="indefinite"/>
  </g>

  <!-- 花朵装饰 -->

  <g transform="translate(40, 320)">
    <circle cx="0" cy="0" r="5" fill="#E91E63"/>
    <circle cx="-6" cy="-3" r="4" fill="#F48FB1"/>
    <circle cx="6" cy="-3" r="4" fill="#F48FB1"/>
    <circle cx="-4" cy="5" r="4" fill="#F48FB1"/>
    <circle cx="4" cy="5" r="4" fill="#F48FB1"/>
    <circle cx="0" cy="0" r="2.5" fill="#FFEB3B"/>
  </g>
  <g transform="translate(760, 330)">
    <circle cx="0" cy="0" r="5" fill="#FF9800"/>
    <circle cx="-6" cy="-3" r="4" fill="#FFCC80"/>
    <circle cx="6" cy="-3" r="4" fill="#FFCC80"/>
    <circle cx="-4" cy="5" r="4" fill="#FFCC80"/>
    <circle cx="4" cy="5" r="4" fill="#FFCC80"/>
    <circle cx="0" cy="0" r="2.5" fill="#FFF176"/>
  </g>
  <g transform="translate(400, 340)">
    <circle cx="0" cy="0" r="4" fill="#9C27B0"/>
    <circle cx="-5" cy="-2" r="3" fill="#CE93D8"/>
    <circle cx="5" cy="-2" r="3" fill="#CE93D8"/>
    <circle cx="-3" cy="4" r="3" fill="#CE93D8"/>
    <circle cx="3" cy="4" r="3" fill="#CE93D8"/>
    <circle cx="0" cy="0" r="2" fill="#FFEB3B"/>
  </g>
</svg>

### 🦒 梅尔曼 · 🦁 亚历克斯 · 🦓 马蒂 · 🦛 格洛丽亚

</div>

***

## 🍖 来喂喂它们吧！

点一下对应的链接，帮它们找点吃的～

| 动物          | 今日心情    | 最爱食物       | 喂食                                                                                                                              |
| ----------- | ------- | ---------- | ------------------------------------------------------------------------------------------------------------------------------- |
| 🦒 **梅尔曼**  | 🌿 悠闲自在 | 金合欢树叶      | [喂长颈鹿 🍃](https://github.com/你的用户名/你的用户名/issues/new?title=🍃-喂长颈鹿\&body=梅尔曼伸长脖子，开心地吃起了金合欢树叶！🌿)                                 |
| 🦁 **亚历克斯** | 🦁 王者风范 | 牛排（其实最爱寿司） | \[喂狮子 🍖]\(<https://github.com/你的用户名/你的用户名/issues/new?title=🍖-喂狮子&body=亚历克斯："I'm> a star! I'm a lion! 这块牛排... well, 寿司更好吃 🍣") |
| 🦓 **马蒂**   | 😄 活力满满 | 优质干草       | \[喂斑马 🌾]\(<https://github.com/你的用户名/你的用户名/issues/new?title=🌾-喂斑马&body=马蒂兴奋地跑了一圈："自由！自由！I> like to move it move it\~")         |
| 🦛 **格洛丽亚** | 😊 优雅自信 | 水草沙拉       | [喂河马 🥗](https://github.com/你的用户名/你的用户名/issues/new?title=🥗-喂河马\&body=格洛丽亚优雅地品尝着水草沙拉，哼起了小曲~")                                   |

> 💡 **玩法说明**：点击「喂食」链接，开一个 Issue 就算投喂成功啦！
> 每天小动物们的心情都可能变化哦～快来看看今天它们怎么样！



***

## 🛠️ 技术栈

![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS_Code-007ACC?style=for-the-badge\&logo=visual-studio-code\&logoColor=white)
![Windows](https://img.shields.io/badge/-Windows-0078D6?style=for-the-badge\&logo=windows\&logoColor=white)

***

## 📊 GitHub 数据

<div align="center">

![你的 GitHub 数据](https://github-readme-stats.vercel.app/api?username=你的用户名\&show_icons=true\&theme=tokyonight\&hide_border=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=你的用户名\&layout=compact\&theme=tokyonight\&hide_border=true)

</div>

***

<div align="center">

### 🎵 背景音乐：I Like to Move It

*"I like to move it, move it\~\
I like to move it, move it\~\
I like to move it, move it\~\
Ya like to move it!"*

<br />

*Made with ❤️ and a lot of SVG*

</div>
