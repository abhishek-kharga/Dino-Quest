# Dino Quest

A responsive, offline-friendly educational endless runner built with plain HTML, CSS, and JavaScript. The canvas runner is adapted from the uploaded Dino Dash HTML, keeping its jump arc, obstacle spawning, forgiving collision boxes, responsive canvas sizing, and gesture-created synthesized sound.

## Run locally or on Replit

Open `index.html` in a modern browser, or import this folder into Replit and use its static web server. No build step or dependencies are required. Google Fonts are optional; the system font fallback keeps the interface usable offline.

## Files

- `index.html` — semantic page, HUD, overlays, and controls
- `styles.css` — responsive dark interface and game screens
- `game.js` — canvas animation, runner physics, quizzes, progression, and local high score
- `questions.js` — offline question bank, grouped by subject
- `assets/` — reserved for optional artwork or audio files

Controls: Space / Up to jump, Down to duck, P to pause, and touch/click the game canvas to jump. Answer a quiz after each stretch of obstacles; correct answers award points and advance the stage, while incorrect answers cost a life. Collect glowing fossils for bonus points and magnet charge.

High scores are stored in the browser using localStorage. Sound effects are synthesized with Web Audio and start only after user interaction.
