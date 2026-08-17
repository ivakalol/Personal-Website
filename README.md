# 3D Personal Portfolio - Engineering & Design

A high-end, gallery-inspired personal website bridging software engineering, 3D design, and hardware innovation. The experience is driven by a continuous scroll through a monolithic architectural space, combining photorealistic AI-generated backgrounds with ultra-smooth frontend motion.

---

## 🛠 Tech Stack & Ecosystem

### Core Engine & Motion
*   **Frontend Framework:** React & TypeScript.
*   **Local Build Environment:** Vite or Next.js for optimal asset bundling.
*   **Motion & Scroll Engine:** [Anime.js v4](https://animejs.com/) (utilizing native `onScroll` timeline scrubbing for zero-latency UI and background syncing).
*   **Rendering Context:** HTML5 `<canvas>` sequence player for zero-latency forward and reverse scroll scrubbing.

### UI Components, Textures & Shaders
*   **Interactive UI Primitives:** [React Bits](https://reactbits.dev/) (copy-paste React/TypeScript animated components like `SpotlightCard`, `TiltedCard`, and text reveals).
*   **Minimal Preloaders:** [Uiverse Loaders](https://uiverse.io/loaders) (zero-dependency pure CSS loaders for initial asset buffering).
*   **Procedural Noise & Grids:** [fffuel.co](https://www.fffuel.co/) (subtle SVG noise layers and micro-grids to eliminate gradient banding and add tactile grain to titanium panels).
*   **3D / WebGL Particles (Optional):** [Casberry Particles](https://particles.casberry.in/) (isolated WebGL particle modules reserved for dynamic project showcase cards).

### Prototyping & AI Generation
*   **Prototyping & Live Previews:** [Google AI Studio](https://aistudio.google.com/apps) (Build mode) for full-stack React runtime, npm support, and conversational vibe coding.
*   **Photorealistic Background Plates:** Google Flow for generating 8k monolithic architectural assets.
*   **Design & System Mockups:** Figma.
*   **Asset CDN:** Dedicated CDN for streaming uncompressed image sequence frames with instant load speeds.

---

## 🎨 Design System

**Concept:** "The Monolithic Stage" (Gallery Pedestals)  
**Vibe:** Heavy physical presence, museum lighting, brushed titanium, dark negative space.

*   **Primary Canvas:** Deep matte graphite and near-black charcoal (`#121212`).
*   **Architectural Accents:** Brushed steel and dark titanium paneling.
*   **Lighting & Accent Color:** Subtle deep wine-red/burgundy (`#4A0E17`) ambient glows.
*   **Typography:** Warm white (`#F5F5F0`) with generous tracking for maximum legibility.
*   **Surface Texture:** 3% opacity SVG noise overlay generated via `fffuel.co`.

---

## 🚀 Execution Plan & Roadmap

### Phase 1: Design System & Asset Prep
*   Finalize Figma mockups for the "Monolithic Stage" layout (Project cards resting on dark steel pedestals).
*   Generate SVG micro-noise textures using `fffuel.co` to add grain to the dark graphite surfaces.
*   Pick and customize a pure-CSS geometric preloader from `uiverse.io/loaders` (styled with `#4A0E17` burgundy accents).
*   Extract the background elements into a lightweight 5–10 frame ambient loop, or a complete camera-pan sequence for the `<canvas>` player.
*   Prepare the transparent background portrait cutout (`Professional_NoBackground.png`).

### Phase 2: Canvas Engine & Core Layout in Google AI Studio
*   Scaffold the React/TypeScript structure in Google AI Studio.
*   Build the HTML5 `<canvas>` sequence player driven by `anime.js` `onScroll` timeline synchronization.
*   Wire the pinned Hero + About Me sequence:
    *   State 1: Embossed *"SOFTWARE ENGINEER"* + Welcome text.
    *   State 2: Dissolve & shrink hero copy; reveal embossed *"ABOUT ME"* and spartan bio.
    *   State 3: Smooth exit of portrait downwards as the canvas transitions into the Monolithic Stage.
*   Validate z-index layering, frame rates, and smooth scrubbing in live preview.

### Phase 3: Interactive UI Cards & Micro-Interactions
*   Integrate `SpotlightCard` or `TiltedCard` components from `React Bits` for the **Selected Projects** showcase.
*   Add hover states where dynamic rim lighting highlights the brushed metal pedestal under the active project card.
*   Assemble the **Education & Skills** grid and **Work Process** (01 $\rightarrow$ 05) vertical conduit.
*   *(Optional)* Embed an interactive WebGL demo module using `Casberry Particles` inside a specific project showcase card.
*   *(Optional)* Configure an embedded Gemini-powered "Recruiter Chat Concierge" inside Google AI Studio.

### Phase 4: Production Build & Deployment
*   Export the finalized codebase from Google AI Studio directly to GitHub.
*   Set up local Vite/Next.js bundling and verify TypeScript types.
*   Host background frames and high-resolution media on a dedicated CDN for instant load times.
*   Deploy production build to Vercel / Netlify.