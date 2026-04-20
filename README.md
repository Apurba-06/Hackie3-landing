⚡ Hack_IE³ | System Override
    A High-Performance, vision-guided landing page for the ultimate 48-hour neural dive.

🌐 Overview
    Hack_IE³ is a conceptual landing page designed for a high-stakes techno-management hackathon. The design language focuses on a "Cyber-     System" aesthetic, utilizing dark surfaces, neon accents, and interactive 3D elements to provide an immersive user experience.

🚀 Key Features
  1)Interactive 3D Matrix: A real-time 3D Earth model built with Three.js, featuring realistic axial tilt and a pinpoint marker on the         "Drop Zone" (Jadavpur University).
  2)Terminal Registration: A simulated command-line interface for user onboarding, including automated "bypass" sequences and state-            managed input.
  3)System Overclock (Easter Egg): A hidden "Matrix Mode."
  4)Trigger: Type hack anywhere on the page to overclock the system.
  5)Effect: Changes the color palette to Matrix-green, triples particle velocity, and triggers high-frequency audio feedback.
  6)Revert: Type unhack.
  7)Neural Canvas: A dynamic background particle network that reacts to mouse proximity, simulating decentralized node synchronization.
  8)Mobile Optimized: Fully responsive layout with scaled 3D transforms and hidden custom cursors for touch interfaces.

🤖 AI Implementation Disclosure
  As per the Task A requirements, below is the breakdown of how AI was utilized in this project:

  1. 3D Geospatial Mapping
    I used AI to assist in calculating the spherical coordinate conversion logic (calcPosFromLatLonRad). This ensured that the 3D marker       precisely targets 22.4986° N, 88.3714° E on the Three.js sphere.

  2. Audio & Logic Synchronization
    The Web Audio API integration for the hover beeps and the "Overclock" state-switching logic was developed using AI-generated               boilerplate, which I then refined to ensure audio contexts resume correctly after user interaction (handling browser autoplay              policies).

  3. Performance Auditing
    To meet the "Performance and Metrics" rubric, AI helped refactor the requestAnimationFrame loops in the Canvas and Three.js sections       to ensure high FPS on mobile devices without draining battery life.

  4. Glitch CSS Synthesis
    The complex @keyframes for the "HACK_IE³" glitch effect were synthesized with AI to create randomized clip-path offsets that mimic         digital signal interference.

🛠️ Tech Stack
    Frontend: HTML5, CSS3 (Custom Variables/Properties)
    Graphics: Three.js (WebGL), Canvas API
    Interactivity: Vanilla JavaScript (ES6+)
    Audio: Web Audio API

