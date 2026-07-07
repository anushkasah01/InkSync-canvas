🎨 InkSync Atelier

A state-of-the-art collaborative drawing canvas designed for real-time multiplayer sketching, customized with an elegant, classical studio aesthetic.

Designed and developed by Anushka Sah.

🟢Live Demo
🔗https://anushkasah01.github.io/InkSync-canvas/

🏛️ Project Overview
<img width="1600" height="713" alt="image" src="https://github.com/user-attachments/assets/8a80db06-5078-420d-85c7-2ce75818cfe7" />


InkSync Atelier transforms the traditional digital whiteboard concept into a high-end physical art studio experience, allowing creators to collaborate asynchronously or synchronously on a virtual stretched linen canvas. Built around a structured 4-Sprint Model, this web application integrates high-fidelity vector drawing, robust state management, and real-time synchronization.

✨ Core Features

Atmospheric Atelier UI: Features classical typography (Playfair Display & Cormorant Garamond), glossy hand-mixed oil paint palette swatches, and a responsive stretched-paper canvas supporting light and obsidian gallery dark modes.

Vector Drawing Engine: High-frequency path tracking for a Charcoal Brush and Eraser, alongside fully responsive drag-to-draw tools for Lines, Rectangles, Circles, and Cursive Text Stamps.

Real-Time Multiplayer Sync: Built-in Firebase Firestore Sync for live peer cursor tracking, automated canvas stroke reconstruction/replay for new room joiners, and a real-time collaborative chat sidebar.

Atelier Bot Companion: An autonomous sketch assistant that draws geometric flower loops, shares classical art quotes inside the chat, and triggers cascading emoji reactions.

Audio Synthesis & Export: Procedural audio feedback generated entirely in-browser via the Web Audio API and instant high-resolution PNG image exports.

Local Portfolio Gallery: Supports saving, loading, and managing custom sketches directly inside the browser's local storage database.

🛠️ Tech Stack

Frontend UI: HTML5, Tailwind CSS, Phosphor Icons

Rendering Engine: HTML5 Canvas API

Collaboration & Storage: Firebase Auth & Firestore (with a fail-safe offline Sandbox Mode)

Procedural Sound: Web Audio API (Oscillator & Gain Nodes)

Local State: LocalStorage API
