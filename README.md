Hand‑Controlled Arpeggiator
A browser‑based music and visualizer app that uses hand gestures to play melodies, drums, and audio‑reactive visuals. Built with Tone.js, Three.js, and MediaPipe Hands.

Features
Play music using hand gestures

Real‑time 3D audio‑reactive visuals

Runs fully in the browser with no backend

Open‑source and customizable

Tech Stack
Tone.js – Audio synthesis and sequencing

MediaPipe Hands – Real‑time hand gesture tracking

Three.js – 3D visualizer

HTML, CSS, JavaScript

Installation
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/collidingScopes/arpeggiator.git
cd arpeggiator
2. Install dependencies
bash
Copy
Edit
npm init -y
npm install --save-dev http-server
3. Add a start script to package.json
json
Copy
Edit
"scripts": {
  "start": "http-server ."
}
4. Start the project
bash
Copy
Edit
npm start
Open http://localhost:8080 in your browser.

How to Play
Allow camera access when prompted.

Use one hand to control the arpeggio (pitch and volume).

Use the other hand to trigger drum patterns.

Enjoy real‑time sound and visuals.

Customization
Change sounds: Edit MusicManager.js to adjust synth settings.

Change drum kits: Replace audio files in /assets/.

Change visuals: Modify WaveformVisualizer.js to tweak the visuals.
