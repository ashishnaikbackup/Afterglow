# Afterglow
A cozy, zero-dependency tabletop and party games lounge built as a single self-contained HTML file. Designed with warm café-paper visuals, switchable ambient backdrops, and procedural Web Audio lo-fi music.
Games Included
Infinite XO — A 3×3 tic-tac-toe variant where each player can hold at most 3 marks on the board. Placing a 4th mark fades and removes your oldest one, eliminating draws. Playable solo against a bot or in 2-player pass-and-play.
Truth & Dare — A social hangout deck with real-life prompts across Hangout, Late Night, and Wild moods. Add up to 8 players and spin the compass to pick who's up next.
Memory Deck — A 16-card 3D-flipping matching game with custom line-art icons, playable solo or in 2-player pass-and-play (matching a pair keeps your turn).
Four-in-a-Row — A 7×6 token-drop board playable solo against a bot or in 2-player pass-and-play.
Atmosphere & Audio
Three Switchable Backdrops: Rainy Café, Mountain Cabin, and Seaside Patio rendered on an HTML5 <canvas> with delta-time animation.
Procedural Audio: Built-in Web Audio API synthesizer generating soft lo-fi chord progressions, gentle ambient rain/wind noise, and tactile sound effects—no external audio files required. Both music and SFX can be toggled independently from the top bar.
Quick Start
No build step, package manager, or backend is needed.
Rename afterglow.html to index.html (optional, recommended for GitHub Pages).
Open the file directly in any modern browser to play locally.
Deploy to GitHub Pages
Push index.html and README.md to a GitHub repository.
Open Settings → Pages in your repository.
Under Build and deployment, select Deploy from a branch, choose main (/ (root)), and click Save.
Your live link will be available at https://<your-username>.github.io/<repo-name>/.
Tech Stack
Vanilla HTML5, CSS3, and ES6 JavaScript
HTML5 <canvas> for ambient backgrounds
Web Audio API for procedural music and sound effects
Inline SVG icons and Google Fonts (Newsreader & DM Sans)
License
MIT
