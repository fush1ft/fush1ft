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
  </svg>
</div>

<!-- ==================== SIGNATURE BLOCK ==================== -->
```txt
[!] N3xt t1m3, p4tch 1t b3f0r3 1 d0.
     Signed: Fush1ft_404
👋 About / O mně
⚙️ Builder • 🧪 Experimenter • 🚀 Always shipping
I build tools, tinker with hardware (ESP32), and learn security by doing. Clean code, reproducible experiments, and responsible chaos.
Signal over noise. Curiosity over ego. Consistency beats hype. 😈✨

📊 Live GitHub Stats & Widgets (auto-updating)
<p align="center"> <!-- GitHub readme stats --> <img align="center" src="https://github-readme-stats.vercel.app/api?username=Fush1ft&show_icons=true&theme=radical&hide_border=true" alt="Fush1ft's GitHub stats" /> <!-- Streak and Top langs --> <img align="center" src="https://streak-stats.demolab.com?user=Fush1ft&theme=radical&hide_border=true" alt="streak stats" /> <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Fush1ft&layout=compact&theme=radical&hide_border=true" alt="top langs" /> </p> <!-- activity graph (contribution heatmap like widget) --> <p align="center"> <img src="https://activity-graph.herokuapp.com/graph?username=Fush1ft&width=900&height=160&theme=react-dark" alt="contribution graph" /> </p>
🛠 Tech Stack / Nástroje
<p> <img src="https://img.shields.io/badge/Linux-000?style=for-the-badge&logo=linux" alt="Linux" /> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/Kali-264653?style=for-the-badge&logo=kalilinux&logoColor=white" alt="Kali" /> <img src="https://img.shields.io/badge/ESP32-2C9F6A?style=for-the-badge" alt="ESP32" /> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" /> <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android" /> </p>
🚀 Featured Projects / Vybrané projekty
🔒 FUParental — private parental control (Android app + home server)

⚡ ESP32 Experiments — sensors, OTA, WiFi exploits & fun

🧪 Security Labs — lab exercises, BeEF tweaks, Bettercap scripts

Pinned repos:
FUParental • esp32-experiments • security-labs

🔁 Auto-updating sections (examples)
WakaTime coding activity (use the WakaTime action below to populate).

Now-playing (Spotify) widget (requires setting up secrets).

Commit cadence + monthly metrics via Actions.

Example: WakaTime live section (auto):

<!-- WakaTime section inserted by GitHub Action --> <!--START_SECTION:waka--> <!--END_SECTION:waka-->
⚡ GitHub Actions (recommended)
Add .github/workflows/update-readme.yml to auto-update WakaTime / activity sections:

yml
Copy code
name: Update README & WakaTime

on:
  schedule:
    - cron: '0 */6 * * *'    # every 6 hours
  workflow_dispatch:

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - name: Update waka & stats
        uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
Add WAKATIME_API_KEY to repo secrets to enable coding-time metrics.
Optional: add Spotify token and other secrets for more widgets.

🎧 Now Playing / Music widget
(If you use Spotify, set up a small Action to push now-playing badge)
Example badge (third-party service):
![Spotify](https://spotify-now-playing-git-main-username.vercel.app/api/spotify)
(requires external setup — skip if you want everything local)

✨ Extra animated SVG widgets (paste anywhere)
Animated "patch" badge (SVG)
html
Copy code

🧪 Philosophy / Filozofie
Build first. 🛠️

Measure reality. 📏

Patch fast. ⚡

Repeat. 🔁

Perfection is a direction, not a state. Keep shipping. 🚀

📬 Contact / Social
GitHub: github.com/Fush1ft

YouTube/Alias: Fushift

Signed: Fush1ft_404 🖋️

🧩 Final magic (badge & CI)
<p align="center"> <img src="https://visitor-badge.glitch.me/badge?page_id=Fush1ft.Fush1ft" alt="Visitors" /> &nbsp; <img src="https://github.com/Fush1ft/Fush1ft/actions/workflows/update-readme.yml/badge.svg" alt="CI Status" /> </p>
