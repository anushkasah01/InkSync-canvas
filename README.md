🎨 InkSync Atelier

Where Fine Art Meets Real-Time Fluid Expression.

A state-of-the-art collaborative drawing canvas designed for real-time multiplayer sketching, customized with an elegant, classical studio aesthetic.

✒️ Signature Credit

This collaborative masterpiece was meticulously crafted, debugged, and polished by Anushka Sah.

🏛️ Project Overview

InkSync Atelier is an immersive, multi-tool web application built around the 4-Sprint Model outlined in InkSync Project (1).docx. It transforms the traditional digital whiteboard concept into a high-end physical art studio experience, allowing creators to collaborate asynchronously or synchronously on a virtual stretched linen canvas.

With built-in Firebase Firestore Sync, an Atelier Bot Companion, satisfying Web Audio Synthesizers, and a Local Artist Gallery, this platform offers a comprehensive interactive space right from the browser.

✨ Features That Make It Stand Out

1. 🌿 Atmospheric Atelier UI & Onboarding

Classical Typography: Elegantly stylized with Google Fonts' Playfair Display (for museum-style headings), Cormorant Garamond (for artistic subtitles), and Plus Jakarta Sans (for clean responsive UI).

Hand-mixed Oil Swatches: Digital color options styled as organic, asymmetrical glossy oil paint dollops with light-reflecting highlights.

Parchment Linen Backdrop: Subtle vector-linen textures (#faf6f0) and deckled edge paper layout components.

Dark & Light Modes: Seamless transition from warm gallery canvas to an obsidian, high-contrast dark room.

2. 🛠️ Complete Vector & Drawing Engine (Sprints 1 & 2)

Precision Brushes: High-frequency path tracking for the standard Charcoal Brush and Eraser with accurate point-clicking support.

Geometric Drafting Suite: Fully responsive vector creation for Lines, Rectangles, and Circles that draw smoothly on drag.

Cursive Text Stamps: Place custom textual annotations anywhere on the canvas instantly.

20-Step History Buffer: Secure undo (Ctrl + Z) and redo (Ctrl + Y) navigation on the active board.

3. 🌐 Real-Time Multiplayer Integration (Sprint 3)

Dynamic Identity Lobby: Customize your unique artist profile on entering with custom SVG aura fields, avatar emoji tags, and randomized classic artist handles (e.g., Sienna Claude, Cobalt Monet).

Live Peer Cursor Tracking: Watch other room members move across the board with real-time vector cursor tracking.

Stroke Replay Engine: As new players join an ongoing room, the board automatically streams and reconstructs the canvas strokes chronologically.

4. 💬 Atelier Discussion & Reactions

Responsive Slide-Over Chat Drawer: Mobile-first slide drawer with system entry log announcers and color-coded chat bubbles.

Floating Emoji Reactions: Click emojis (👍, 🎉, 🔥, 😮, 🎨) to send cascading, floating reaction nodes directly into everyone's viewport.

5. 🤖 Atelier Bot Companion

Toggle Play with Bot to invite Atelier Bot 🤖 onto the canvas!

The bot autonomously:

Sketches geometric flower loops, bursts, and stamp patterns.

Shares classic art quotes from famous masters inside the chat thread.

Triggers cascading emoji reactions when players draw.

6. 🔊 Synthesizer Audio & Exports (Sprint 4)

In-Browser Audio Engine: Lightweight sound design elements synthesized procedurally via the Web Audio API—no heavy asset downloads required.

Local Portfolio Gallery: Save files dynamically to the browser's local storage database; load, review, or clear drawings at any time.

PNG Canvas Exports: Instant snapshot downscaling and image output rendering for direct sharing.

🛠️ Technical Stack & Architecture

Frontend UI: Responsive Tailwind CSS with custom theme extensions.

Icons: Phosphor Web Icons integration.

Collaboration: Dynamic Firebase Firestore integration.

Procedural Audio: Native Web Audio API Oscillator Nodes.

Storage: LocalStorage API for local artwork folders.

🛡️ Core Stability Layer (Iframe & Race-Condition Safe)

Document Load Race-Condition Patch: To safely handle iframe render environments, the main entry point runs directly on document.readyState validations instead of standard async events.

Dynamic Fail-Safe CDNs: Firebase dependencies are loaded via safe, asynchronous import() syntax. If Google CDNs are firewalled or blocked, InkSync Atelier automatically detects the error, displays an aesthetic toast notification, and switches seamlessly to a fully active Local Sandbox Mode so the website never crashes.

📅 Sprint Model Alignment

This project satisfies and extends the structured development milestones of the 4-Sprint Model from InkSync Project (1).docx:

Sprint Phase

Milestone Description

Implementation in InkSync Atelier

Sprint 1

Canvas Setup & Basic Drawing

High-resolution HTML5 Canvas with Charcoal, paint-weight sizing, and color picking.

Sprint 2

Tools & Canvas Features

Eraser tool, complete Clear functionality, and 20-step local Undo/Redo tracking.

Sprint 3

Real-Time Collaboration

Room generation, shared Live Chat, dynamic custom peer-cursors, and Firebase stroke sync.

Sprint 4

Polish & Export Features

In-browser synthesizer SFX, Local Gallery drawer, PNG Exports, and a companion Bot.

Created with passion, art, and modern tech standards by Anushka Sah.
