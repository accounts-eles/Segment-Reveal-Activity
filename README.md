🎡 Segment Reveal Activity Template

An interactive "arch-dial" interface designed for binary comparisons or dual-topic exploration. This template features a unique semi-circular "wheel" layout that allows users to toggle between two distinct segments to reveal contextual information beneath.

🚀 Live Demo

Explore the Segment Reveal Interface Here

✨ Project Overview

The Segment Reveal template is optimized for presenting two sides of a concept—such as "Problem vs. Solution," "Pros vs. Cons," or "Means vs. Implications." By using a semi-circular visual metaphor, it creates a focused, high-contrast environment for learning.

Key Features

Arch-Dial Navigation: A visually striking semi-circular wrapper divided into interactive segments with custom text offsets for optical centering.

Progressive Disclosure: Uses a slide-up fade animation to reveal complex information only when the user selects a specific segment.

Branded Visual Identity: Consistent with the professional ecosystem design:

Midnight Blue (#1f2a52): Primary segment background and main headings.

Accent Teal (#00bec7): High-visibility active state and list indicators.

Light Aqua (#d2f0f0): Soft background for revealed content to ensure high legibility.

Slate Grey (#abb5bf): Secondary segment background and instruction text.

Compact Content Design: Specifically designed with reduced padding and streamlined list styling to present significant information within a limited viewport.

🛠️ Technical Implementation

Geometric Layout: Employs CSS border-radius and overflow management to create the semi-circular "wheel" effect.

Active State Logic: Vanilla JavaScript handles mutually exclusive states, ensuring that selecting one segment automatically deactivates the other to maintain focus.

Responsive Breakpoints: Includes a dedicated mobile media query that transforms the fixed-width wheel into a fluid container with adjusted typography for smaller touch targets.

CSS Keyframes: Utilizes a slideUpFade animation for a smooth, modern transition when content is revealed.

📂 Project Structure

Segment-Reveal-Activity/
├── index.html          # Core template, arch-dial logic, and styles
├── previews/           # Automated UI capture assets
└── .github/workflows/  # CI/CD for catalog and preview synchronization


🤖 Catalog Integration

This repository is part of the Catalog of Repos ecosystem. The automated workflows are configured to capture both active states of the wheel to demonstrate the toggle functionality in the global gallery.

📄 License

MIT License - Created for the accounts-eles ecosystem.
