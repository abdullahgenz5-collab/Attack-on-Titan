# ⚔️ Attack on Titan — Scroll-Driven Tribute

> A cinematic, scroll-driven tribute website built with pure HTML, CSS, and Vanilla JavaScript. No frameworks, no dependencies — just raw web performance.

### 🌐 [👉 View Live Demo](https://abdullahgenz5-collab.github.io/E-Comerace/) 

---

## ✨ Features & Enhancements
- 🎵 **Dynamic Sound System:** Integrated cinematic audio (Background music, Titan roars, thunder, and ODM gear sounds) triggered by scroll interactions and user clicks.
- 🌍 **Fully Localized:** Translated all original Japanese text into immersive, lore-accurate English descriptions.
-  **Enhanced UI/UX:** Added a custom cinematic scrollbar, glowing text animations, an audio toggle button, and a smooth "Back to Top" feature.
- ⚡ **Zero Dependencies:** Built with pure Vanilla JS, HTML5 Canvas, and WebGL (No React, No jQuery, No heavy libraries).
- 📱 **Responsive Design:** Optimized for both desktop and mobile viewports with reduced-motion accessibility support.

---

##  The Three Acts

| Act | Section | Effect |
|---|---|---|
| **I** | `#wall` | 71-frame scroll-scrub of the Colossal Titan. Features screen shake, chromatic ghosting, steam particles, and a shockwave at the breach. |
| **II** | `#eren` | 32-frame scroll-scrub of the Attack Titan transformation. Features procedural lightning bolts and flash frames tied to scroll progress. |
| **III**| `#reveal` | Interactive cursor-trail reveal effect, carving through darkness to reveal hidden imagery dynamically. |

*Between the acts: A scroll-velocity marquee, a four-layer parallax wall field, and a WebGL aurora finale.*

---

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone hhttps://abdullahgenz5-collab.github.io/Attack-on-Titan/
   cd E-Comerace
   Open in VS Code:
Install the Live Server extension.
Right-click on index.html and select "Open with Live Server".
(Alternatively, run npx serve . or python -m http.server 5173 in your terminal).
⚠️ Note: Opening index.html directly via file:// might block audio and image decoding due to browser CORS policies. Always use a local server.
📂 Project Structure
├── index.html       # Main HTML structure & semantic layout
├── style.css        # Enhanced custom styling, animations & responsive design
├── main.js          # Vanilla JS logic, scroll-scrubbing, canvas rendering & audio system
└── assets/          # Media folder
    ├── frames/      # Scroll-scrub image sequences (desktop & mobile)
    ── reveal/      # Images for the interactive cursor-trail reveal section
    🛠️ Credits & Inspiration
Original Concept: Inspired by advanced scroll-driven web design techniques and reactbits.dev components (ported to dependency-free vanilla JS).
Customizations by: Abdullah (English Translation, Audio Integration, UI/UX Polish, and Performance Tuning).
Audio Sources: Royalty-free cinematic sounds via Pixabay.
Made with ❤️, a lot of ☕, and the spirit of the Survey Corps.
Shinzou wo Sasageyo! 🪽