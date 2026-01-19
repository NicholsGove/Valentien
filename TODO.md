# Valentine's Proposal Website - TODO

This document tracks the implementation steps for the romantic interactive Valentine's proposal website using pure HTML, CSS, and JavaScript.

## Plan Checklist

- [x] Create `index.html` with three screens:
  - [x] Intro Screen with centered text "Click here to continue ❤️"
  - [x] Question Screen with typewriter question and Yes/No buttons
  - [x] Celebration Screen with big romantic message and effect containers
  - [x] Global floating heart background container
  - [x] Link Google Font (Great Vibes), `style.css`, and `script.js`
  - [x] Optional <audio> element for soft background music (muted initially)

- [x] Implement `style.css`:
  - [x] Define CSS variables for romantic theme (soft pinks, reds, whites)
  - [x] Global styles: cursive font, smooth transitions, rounded corners everywhere
  - [x] Layout and responsiveness using Flexbox and `clamp()` for font sizes
  - [x] Intro background floating hearts with blur and fade
  - [x] Screen transitions (fade/slide)
  - [x] Buttons with hover bounce and glow
  - [x] Neon pulse animation for Yes button
  - [x] Bright neon arrows styling and animations
  - [x] Confetti, sparkles, and floating hearts keyframes

- [x] Implement `script.js`:
  - [x] Screen navigation and transitions (intro → question → celebration)
  - [x] Typewriter effect for "Will you be my Valentine?"
  - [x] No-button logic: rotate messages and then show arrows + neon Yes button
  - [x] Yes-button: transition to celebration and trigger effects
  - [x] Generators for floating hearts, confetti, and sparkles with randomization
  - [x] Autoplay background music muted, unmute on first user interaction (click)
  - [x] Accessibility: focus management and ARIA updates

- [x] Valentine enhancements (Feb 2026):
  - [x] Dark romantic gradient background (burgundy → rose)
  - [x] Background hearts +40% size, infinite rise, and remain visible with a cap to avoid growth
  - [x] Interactive buttons: 3D tilt on hover, glossy shine sweep, click ripple, and mini-heart burst
  - [x] Prefers-reduced-motion respected for all new effects

- [ ] Test and refine:
  - [ ] Verify smooth animations and transitions on desktop and mobile
  - [ ] Validate responsiveness and readability
  - [ ] Confirm glow and neon feel looks premium and soft
  - [ ] Ensure no external frameworks are used (only Google Fonts)

## Notes

- The font used: "Great Vibes" from Google Fonts (cursive for all text).
- Color palette: Soft pinks/reds/whites with glow accents.
- All elements should have rounded corners and soft shadows for a romantic, premium feel.
