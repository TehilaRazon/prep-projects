# Magic Card Project

An interactive, accessible landing page card component built with pure HTML and CSS.

## 🎨 Design Choices
- **Theme**: Dark gradient background (`#0f172a` to `#1e293b`) with a warm beige card for high contrast and readability.
- **Hover State**: Inverts background and text colors while performing a 360° rotation.

## 🎬 Animations & Durations
- **Entrance (`appear`)**: 2-second fade-in and scale-up animation on page load.
- **Continuous Motion (`slide`)**: 4-second smooth horizontal floating animation (`infinite alternate`).
- **Hover Interaction**: 0.8-second transition for smooth rotation and color change, with `animation-play-state: paused` to prevent animation conflicts.

## ♿ Accessibility
- Implemented `@media (prefers-reduced-motion: reduce)` to disable all animations and transitions for users who prefer reduced motion.
