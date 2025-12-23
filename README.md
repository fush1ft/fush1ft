<!-- ================================================== -->

<!--                 Fush1ft_404 — Super Profile         -->

<!--   Paste this entire file into README.md of repo    -->

<!--        named exactly: github.com/Fush1ft/Fush1ft    -->

<!-- ================================================== -->

<!-- ==================== ANIMATED SVG HEADER ==================== -->

<div align="center">
  <!-- Inline SVG header with animated gradient + orbiting dots -->
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 220" width="100%" style="max-width:900px;">
    <defs>
      <linearGradient id="lg" x1="0" x2="1">
        <stop offset="0%" stop-color="#00f5ff">
          <animate attributeName="stop-color" values="#00f5ff;#7cff00;#ff66a3;#00f5ff" dur="6s" repeatCount="indefinite"/>
        </stop>
        <stop offset="100%" stop-color="#7cff00">
          <animate attributeName="stop-color" values="#7cff00;#ff66a3;#00f5ff;#7cff00" dur="6s" repeatCount="indefinite"/>
        </stop>
      </linearGradient>

```
  <filter id="glass" x="-20%" y="-20%" width="140%" height="140%">
    <feGaussianBlur in="SourceGraphic" stdDeviation="1.2" result="b"/>
    <feSpecularLighting in="b" surfaceScale="2" specularConstant="0.4" specularExponent="15" lighting-color="#ffffff">
      <fePointLight x="-5000" y="-10000" z="20000"/>
    </feSpecularLighting>
  </filter>

  <g id="dot">
    <circle r="6" fill="#fff" opacity="0.95"/>
  </g>
</defs>

<rect width="100%" height="100%" fill="#0b0f13"/>

<!-- animated title -->
<text x="50%" y="42%" text-anchor="middle" font-family="Consolas,monospace" font-size="36" fill="url(#lg)" style="letter-spacing:2px;">
  Fush1ft_404
</text>
<text x="50%" y="62%" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, " font-size="14" fill="#9aa7b2" opacity="0.9">
  Build • Break • Learn  —  Patch it before I do.
</text>

<!-- orbiting animated dots for motion -->
<g transform="translate(500,120)">
  <g transform="rotate(0)">
    <use href="#dot" x="-220" y="0">
      <animateTransform attributeType="XML" attributeName="transform" type="rotate" from="0" to="360" dur="16s" repeatCount="indefinite"/>
    </use>
  </g>
  <g transform="rotate(0)">
    <use href="#dot" x="0" y="-90" opacity="0.85">
      <animateTransform attributeType="XML" attributeName="transform" type="rotate" from="360" to="0" dur="10s" repeatCount="indefinite"/>
    </use>
  </g>
  <g transform="rotate(0)">
    <use href="#dot" x="180" y="20" opacity="0.7">
      <animateTransform attributeType="XML" attributeName="transform" type="rotate" from="0" to="360" dur="22s" repeatCount="indefinite"/>
    </use>
  </g>
</g>

<!-- subtle moving grid lines -->
<g stroke="#0f1720" stroke-width="0.6" opacity="0.6">
  <line x1="0" y1="200" x2="1000" y2="200">
    <animate attributeName="x1" values="0; -40;0" dur="8s" repeatCount="indefinite"/>
  </line>
</g>
```

  </svg>
</div>

<!-- ==================== SIGNATURE BLOCK ==================== -->

```txt
[!] N3xt t1m3, p4tch 1t b3f0r3 1 d0.
     Signed: Fush1ft_404
```
