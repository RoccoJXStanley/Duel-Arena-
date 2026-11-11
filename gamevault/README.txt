GAMEVAULT - your personal game launcher
=======================================

EASIEST WAY (no install):
  Double-click index.html. It opens in your browser. Keep the "games" folder next to it.
  (Your games load three.js and fonts from the internet, so you need to be online.)

REAL DESKTOP APP (own window, own icon, installer):
  1. Install Node.js from https://nodejs.org (the LTS version).
  2. Open a terminal in this folder and run:
        npm install
        npm start          <- launches GameVault as a desktop app
  3. To make an installer you can keep (.exe on Windows, .dmg on Mac):
        npm run build      <- the installer appears in the "dist" folder

ADDING MORE GAMES:
  Put the .html file in the "games" folder, then copy one entry in the GAMES list
  at the top of the <script> in index.html and change the title, file, and colors.

TIPS:
  - Hover at the very top of the screen while playing to get Exit / Fullscreen buttons.
  - F11 toggles fullscreen in the desktop app.
