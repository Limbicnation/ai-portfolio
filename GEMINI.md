# GEMINI.md

## Project Overview

**ai-portfolio** is a static portfolio website for Gero Doll ("Limbicnation"), a Senior Technical Artist and Generative AI Specialist. The portfolio showcases work in generative AI, LoRA training, video synthesis, and 3D visualization.

The project adheres to a "crystal consciousness" aesthetic, utilizing a dark theme with cyan accents. It is designed to be minimal, fast, and easy to deploy without complex build steps.

## Architecture

This is a purely static frontend project with no backend or build system requirements.

*   **Core Technology:** HTML5, CSS3.
*   **Styling:** Tailwind CSS (v3) loaded via CDN.
*   **Fonts:** Inter (via Google Fonts).
*   **Structure:** Single-Page Application (SPA) layout implemented in a single `index.html` file.
*   **Assets:** Images are currently loaded from external placeholders or sources; no local asset folder is currently populated in the root.

## Building and Running

Since this is a static site, there is no build process.

### Running Locally

You can simply open the `index.html` file in any modern web browser.

Alternatively, to simulate a production environment or avoid local file restriction issues (CORS), run a simple HTTP server in the project root:

```bash
# Python 3
python3 -m http.server

# Node.js (if available)
npx serve
```

Then navigate to `http://localhost:8000` (or the port specified by the server).

## Key Files

*   `index.html`: The complete source code for the website, containing structure, content, and embedded custom styles.
*   `CLAUDE.md`: Contains contextual guidelines for AI assistants (specifically Claude) regarding project tone and structure.
*   `README.md`: General project description and public-facing documentation.

## Development Conventions

*   **Single-File Architecture:** Keep the project self-contained in `index.html` unless the complexity grows significantly.
*   **Styling:** Use Tailwind utility classes for most styling. Use the `<style>` block in `index.html` for global overrides, specific animations, and the **Projects Section** (which uses vanilla CSS for a custom, lightweight design).
*   **Theme:** Strictly adhere to the **Dark Mode** aesthetic (bg-gray-900) with **Cyan** (cyan-400/500) accents.
*   **Responsiveness:** Ensure all sections (Hero, About, Projects) are fully responsive, adopting a mobile-first approach.
*   **Content:** Maintain the professional yet "mystical/technical" tone described in the project documentation.
