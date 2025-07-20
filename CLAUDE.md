# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static portfolio website for "Limbicnation" - an AI researcher and creative technologist specializing in generative AI, LoRA training, and crystal consciousness exploration. The portfolio showcases fractal cube generators, video synthesis, and multimodal AI projects.

## Architecture

The project is intentionally minimal:
- **Static HTML/CSS/JS only**: Single `index.html` file with embedded styles
- **Frontend Framework**: Tailwind CSS (loaded via CDN)
- **No build process**: Direct HTML file that can be opened in browser or served statically
- **No backend dependencies**: Pure frontend implementation

## Project Structure

```
ai-portfolio/
├── index.html      # Main portfolio page (complete single-page application)
├── README.md       # Project description
└── LICENSE         # Project license
```

## Development Workflow

Since this is a static HTML project:

1. **Local Development**: Open `index.html` directly in a web browser
2. **No build commands needed** - all changes are immediate
3. **No package managers** - dependencies loaded via CDN
4. **No testing framework** - visual testing by opening file in browser

## Technical Details

- **Styling**: Tailwind CSS v3 via CDN, custom Inter font from Google Fonts
- **Layout**: Responsive design with mobile-first approach
- **Sections**: Header navigation, hero, about, projects showcase, contact
- **Interactive Elements**: Smooth scrolling, hover effects, responsive navigation
- **Color Scheme**: Dark theme (gray-900 background, cyan accents)

## Content Focus

The portfolio emphasizes:
- AI/ML specializations (LoRA training, video synthesis, generative models)
- Creative technology projects (fractal generators, architectural concepts)
- Tools mentioned: PyTorch, Diffusers, ComfyUI, HunyuanDiT, Blender
- Philosophy: "Crystal consciousness meets generative AI"

## Editing Guidelines

When making changes:
- Maintain the single-file architecture unless absolutely necessary
- Preserve the dark theme and cyan accent color scheme
- Keep the mystical/technical tone ("crystal consciousness", fractal themes)
- Ensure responsive design works across devices
- Maintain smooth animations and hover effects