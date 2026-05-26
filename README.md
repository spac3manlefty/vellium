# 🌌 Vellium v4

Vellium v4 is a high-performance, single-page web workspace utility hub designed to aggregate links, games, and web diagnostic utilities into a highly responsive, custom-stylized control environment. Built entirely with vanilla HTML5, CSS3 variables, and modern asynchronous JavaScript, Vellium eliminates jarring browser redirects by utilizing an isolated inside-the-app iframe execution layer.

---

## 🚀 Key Features

- **Columnar Workspace Viewport**: Intercepts link click events and safely serves targets within a clean, fast-loading `<iframe>` canvas embedded directly inside the main column area.
- **Floating Network Controller**: Features a top control header for active embedded targets that displays the target path, provides one-click reloads, contains an external tab breakout function, and includes an absolute teardown mechanism (`Close Frame`) to instantly flush frame memory.
- **Dynamic Context Header Items**: Includes an active digital clock engine running in a 12-hour format, accompanied by a dynamic **Discord server shortcut link** that cleanly unmounts from view during active game/proxy sessions to maximize viewport space.
- **Target Link Interception Diagnostics**: An asynchronous, local network diagnostic test module utilizing fetch endpoints, automatic timeouts (3000ms), and error handling to evaluate local filter agent nodes (e.g., Lightspeed nodes) and map latency profiles.
- **Live Theme Customizer Canvas**: Built completely around modular CSS `:root` variables, providing structural control over wallpapers, panel backgrounds, button borders, hover highlights, and font sizes globally in real-time.
- **Interactive FX Engine**: Utilizes an advanced HTML5 canvas layer paired with high-frequency math animations to execute custom particles and structural glitter bursts tied to element interaction points.

---

## 🛠️ Tech Stack & Architecture

- **Markup & Layout**: Semantically structured HTML5 elements combined with CSS Flexbox and Grid layouts for fluid responsiveness.
- **Styling Architecture**: Driven entirely by CSS Variables (`--bg-color`, `--accent-purple`, etc.) to facilitate instant global DOM painting upon property adjustments.
- **Scripting Engine**: Modular Vanilla ECMAScript (JavaScript) utilizing modern features like `async/await`, the `AbortController` API for timeouts, real-time event delegation, and `requestAnimationFrame` hooks to drive responsive interface canvas physics smoothly.

---

## 📂 File Directory Overview

```text
├── index.html          # Core single-page application entry point containing layout, styles, and scripts
└── README.md           # Documentation and structural overview file
