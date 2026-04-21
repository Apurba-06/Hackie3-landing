# 💻 HackIE³ | System Override

> *A 48-hour neural dive into the future of decentralized tech, AI, and systems architecture. No limits. No boundaries. Code the impossible.*

HackIE³ is a fully immersive, interactive, and highly optimized cyberpunk-themed hackathon landing page. Built entirely with Vanilla HTML, CSS, and JavaScript in a single file, it features 3D rendering, a custom audio engine, particle networks, and hidden terminal easter eggs.

## ✨ Features

**Visual & UI Engineering**
* **Immersive Preloader:** Sequential boot-up screen simulating a mainframe connection.
* **Interactive 3D Globe:** Built with `Three.js`, featuring an additive-blend atmosphere, a custom marker for Jadavpur University, and a wireframe fallback.
* **Canvas Particle Network:** A dynamic, physics-based background network that reacts to cursor proximity.
* **Cyberpunk Aesthetics:** CRT scanline overlays, glowing neon section dividers, glitch-text animations, and a responsive scroll-progress bar.
* **3D Tilt Mechanics:** Hover-responsive 3D tilt effects on Bounty and Judge cards.
* **Magnetic Elements:** Navigation links and buttons that magnetically pull toward the user's cursor.

**Interactive Systems**
* **Matchmaking Terminal:** A functional, simulated command-line modal for "registration." Includes email regex validation, scrolling text generation, and interactive prompts (SOLO vs SQUAD).
* **Time-Aware Schedule:** The timeline reads the system clock to automatically highlight the currently "LIVE" event with glowing badges and grays out past events.
* **Live Countdown:** Real-time countdown ticking down to the system start (June 5, 2026).

**Audio Engine**
* **Web Audio API Integration:** Synthesized, dynamic hover beeps that change pitch based on the system state.
* **Ambient Server Drone:** A toggleable, low-frequency synthetic ambient background drone that mimics the hum of a server room.

**Accessibility (a11y)**
* Fully responsive design (Mobile, Tablet, Desktop).
* Respects `@media (prefers-reduced-motion: reduce)` by disabling heavy animations, 3D renders, and flashing lights for sensitive users.
* Includes ARIA labels, semantic HTML, and a "Skip to main content" link for screen readers.

## 🕵️‍♂️ Hidden Easter Eggs

Try these out when you load the page:
1. **Matrix Overclock Mode:** Type `hack` anywhere on your keyboard. The system will "overclock," turning the UI green, speeding up the particle network, and changing the audio pitch. Type `unhack` to revert to the standard protocol.
2. **Terminal Defiance:** Open the Connect terminal and type `sudo` to see what happens.
3. **Clear Terminal:** Type `clear` in the terminal to wipe the logs.

## 🛠 Tech Stack

* **Structure:** HTML5
* **Styling:** Pure CSS3 (Custom properties, Keyframe animations, CSS Grid/Flexbox)
* **Logic:** Vanilla JavaScript (ES6+)
* **3D Library:** [Three.js](https://threejs.org/) (via CDN)
* **Fonts:** Google Fonts ('Orbitron' & 'Share Tech Mono')


