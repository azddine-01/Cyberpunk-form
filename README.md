# Cyberpunk-form

A neon, cyberpunk-styled HTML/CSS form UI template. This repository contains a small, static form built with HTML and CSS that demonstrates a retro-futuristic, neon-styled design suitable for landing pages, sign-up forms, or UI experiments.

Languages
- CSS
- HTML

Design

This project focuses on a cohesive cyberpunk visual design and clear component layout rather than implementation details. The design section describes visual language, components, spacing, typography, color usage, and interaction states so contributors and designers can keep implementations consistent.

- Visual language
  - Mood: dark, neon-lit, futuristic — high-contrast UI elements sitting on a deep multi-stop background.
  - Accents: saturated magenta/pink and cyan/teal are the primary accent colors. Use these for focal elements (primary buttons, highlights, selected states).
  - Material: semi-translucent "glass" panels (glassmorphism) for main cards with subtle borders and blur to separate layers.

- Layout & spacing
  - Card-centered layout: the form is placed in a centered card with a max width around 400–480px for comfortable reading and input spacing.
  - Rhythm: vertical spacing uses a consistent scale (8px baseline) — typical gutters are 12–24px between text, inputs and actions.
  - Alignment: labels left-aligned above inputs for clarity; action buttons full-width below fields for mobile friendliness.

- Typography
  - Primary font: modern, geometric sans-serif (Inter, Roboto, system-ui fallback) for clean UI text.
  - Hierarchy: form titles use a bold, larger size (24–32px), labels and helper text use medium weight (12–14px), input text 14–16px.
  - Letter spacing: slightly tightened for headings and normal for body text to retain readability at small sizes.

- Color & contrast
  - Background: deep, low-saturation gradient to create depth without competing with neon accents.
  - Text: ensure body and label text have sufficient contrast against background (WCAG AA minimum recommended) — reserve neon colors for accents, not primary text.
  - States: define distinct visual states for hover, focus, disabled and error. Focus states should be high-visibility (outline or glow) for accessibility.

- Components
  - Form card: translucent panel with subtle border and drop/glow shadow to read as an elevated surface.
  - Inputs: clear labels, consistent padding, and visible focus ring/glow; support placeholder and helper text beneath inputs.
  - Buttons: primary action uses bold neon gradient or single saturated color; secondary actions use outlined or muted variants.
  - Validation: errors use an accessible red tone with concise messaging and correlate to inputs with aria attributes.

- Motion & interaction
  - Micro-interactions: subtle lift on hover, small translate on click and gentle focus glows improve perceived quality.
  - Avoid heavy motion that distracts or causes motion sickness — keep transitions short (100–200ms) and optional.

- Accessibility
  - Keyboard: full keyboard navigation and visible focus indicators are required.
  - Screen readers: labels bound to inputs and descriptive error messaging via aria-live regions.
  - Contrast: verify color choices against WCAG 2.1 AA; if neon accent is used for information, pair it with text or icon cues.

Preview

Add a preview screenshot in assets/screenshot.png and reference it here to showcase the look:

![Cyberpunk Form Preview](assets/screenshot.png)

Features
- Neon/cyberpunk visual style using CSS gradients, glassmorphism and glows
- Responsive layout for common form sizes
- Easy-to-customize variables for colors and spacing

Quick start
1. Clone the repository:
   git clone https://github.com/azddine-01/Cyberpunk-form.git
2. Open the form in your browser:
   - Open index.html in any modern browser (Chrome, Firefox, Edge, Safari).

Usage
- The project is static — no build tools required. Edit the HTML and CSS files to change content and styles.
- Recommended workflow: use a live-reload extension or a simple static server (e.g., `python -m http.server`) when developing.

Customization
- Colors and glow settings are centralized in the main CSS file. Look for CSS variables (e.g., --accent-color, --bg-gradient) at the top of the stylesheet and adjust them to change the theme quickly.
- Form layout and spacing can be adjusted by editing container width, padding, and font-size rules.

Contributing
Contributions are welcome. Feel free to open issues or submit pull requests to improve styles, accessibility, or add new variants.

Accessibility
- This template focuses on visual style. Please check color contrast and keyboard navigation before using it in production.

License
MIT — see LICENSE file for details.

Contact
Created by azddine-01. For questions or suggestions, open an issue on the repository.