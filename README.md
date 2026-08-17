# 3D Personal Portfolio - Engineering & Design

A high-end, gallery-inspired personal website bridging software engineering, 3D design, and hardware innovation. The experience is driven by a continuous scroll through a monolithic architectural space, combining photorealistic AI-generated backgrounds with ultra-smooth frontend motion.

---

## 🛠 Tech Stack & Tools

*   **Frontend Framework:** React & TypeScript.
*   **Local Build Environment:** Vite or Next.js for optimal asset bundling.
*   **Motion & Scroll Engine:** Anime.js v4 (utilizing the native `onScroll` timeline scrubbing for zero-latency UI and background syncing). 
*   **Rendering Context:** HTML5 `<canvas>` sequence player for the zero-latency forward and reverse scroll scrubbing of background frames.
*   **Prototyping & AI Generation:** 
    *   Google AI Studio (Build mode) for full-stack React runtime, live browser previews, and conversational "vibe coding".
    *   Google Flow for generating photorealistic 8k architectural background assets.
*   **Design & Layout:** Figma for UI mockups.
*   **Asset Hosting:** A dedicated CDN for serving heavy uncompressed image sequence frames instantly.

---

## 🎨 Design System

**Concept:** "The Monolithic Stage" (Gallery Pedestals)
**Vibe:** Expensive studio lighting, physical architectural weight, pure dark negative space.

*   **Primary Background:** Deep near-black charcoal and matte dark graphite (`#121212`).
*   **Architectural Accents:** Brushed steel and titanium paneling.
*   **Lighting & Accent Color:** Subtle deep wine-red/burgundy (`#4A0E17`) ambient glows.
*   **Typography:** Warm white (`#F5F5F0`) for maximum legibility against the dark void.

---

## 🚀 Execution Plan & Roadmap

### Phase 1: Design Finalization & Asset Generation
*   Complete the final Figma mockup for the "Monolithic Stage" concept (Selected Projects resting on dark steel pedestals).
*   Finalize the typography scale, precise spacing, and exact color hex codes in Figma.
*   Generate the final high-resolution background plates in Google Flow.
*   Extract the background elements into a lightweight 5-10 frame ambient loop, or a complete camera-pan sequence for the `<canvas>` player.
*   Prepare the transparent background portrait asset (`Professional_NoBackground.png`).

### Phase 2: Prototyping in Google AI Studio
*   Scaffold the initial React/TypeScript component tree inside Google AI Studio.
*   Instruct the AI to build the HTML5 `<canvas>` sequence player using placeholder images.
*   Implement Anime.js `onScroll` to tie the browser scrollbar directly to the canvas frame progression.
*   Test the z-index layering, camera depth, and typography fade transitions (e.g., the crossfade from "Software Engineer" to "About Me") live in the browser.
*   Convert the UI layouts exported from Figma directly into responsive React components.

### Phase 3: Interactive Features & Refinement
*   Build the interactive hover states for the Project Cards using Anime.js (e.g., lighting up the pedestal or shifting the perspective).
*   **Optional AI Integration:** Build an embedded, micro-styled AI chat widget powered by Gemini, trained specifically on the resume, skills, and Computer Science background as a "Recruiter Chat Concierge".
*   Enforce the strict color palette (`#121212`, `#4A0E17`) across all generated UI sub-components.

### Phase 4: Production Deployment
*   Export the finalized React codebase directly from Google AI Studio to this GitHub repository.
*   Set up the local Vite/Next.js environment.
*   Upload all high-resolution generated background frames and video assets to a CDN for production-level load speeds.
*   Deploy the live site (via Vercel, Netlify, or similar).