# On The Grind - playtest builds

Tony Hawk-style skating game by Ravi (Godot 4). This repo only carries playtest downloads; the source lives in a private repo.

## Play in the browser (experimental)
Open the GitHub Pages site of this repo (https://ravikus1457.github.io/on-the-grind-play/). Chrome or Edge on a desktop, WebGL 2 required; the first load fetches about 46 MB. The browser version is tuned for ordinary work PCs: it loads only the Embarcadero district with flat water and no skyline, on the Low preset with a 0.67 render scale and no traffic; raise Quality in Esc > Settings only if it runs smoothly. Integrated Intel graphics can still stall on the first shader compiles: give it a few seconds after the title screen. It uses the Compatibility renderer, so it looks simpler than the Windows build. Browser controls are the same except Special, which is I in the browser (Ctrl is reserved by browsers); the first-run hints show the right keys.

## Play on Windows
1. Download the newest OnTheGrind-<version>-windows.zip from the Releases page.
2. Unzip anywhere and run OnTheGrind.exe. Windows SmartScreen may warn because the build is unsigned: click "More info" then "Run anyway".
3. Controls are shown on first run (Settings > Controls lets you rebind keys).

## Feedback
Open an issue here with what you saw, your GPU and the OnTheGrind.log file (Windows: %APPDATA%\Godot\app_userdata\On The Grind\).
