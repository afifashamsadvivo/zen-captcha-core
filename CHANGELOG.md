# Changelog

## [1.0.0] - 2026-05-05
### Added
- **Pure Client-Side Logic**: Proof of humanity using only HTML, CSS, and JS.
- **Futuristic UI/UX**: Dark-themed glassmorphic container with "Neon Cyan" accents.
- **Responsive Architecture**: Viewport scaling for mobile/desktop support.
- **Custom Alert System**: Themed "SECURITY BREACH" and "ACCESS GRANTED" overlays.

### Changed
- **Token Display**: Integrated `word-break: break-all` to prevent layout shattering from long tokens.

### Fixed
- Initial release; no previous bugs to fix.

### Security
- **Warning**: This version uses Client-Side Validation only. Server-side verification is not yet implemented.

---

## [26.05] - 2026-05-26
### Added
- **Quantum Clock:** Integrated a real-time UTC+ offset system clock into the UI footer with neon-cyan styling.
- **Dynamic Particle Background:** Deployed a lightweight canvas-based particle field featuring 60 randomized nodes for enhanced immersion.
- **Success Feedback:** Added a "Success Beep" audio confirmation that triggers upon successful human verification.
- **Atmospheric Visuals:** Implemented a vertical scanning line effect and radial pulse-glow animations to simulate active security monitoring.
- **Developer Telemetry:** Added "System Online" console logging to monitor the verification node status in real-time.

### Changed
- **reCAPTCHA Logic:** Modified the `checkCaptcha` function to include an automated `grecaptcha.reset()` call, allowing for instant retries without a page refresh.
- **UI Architecture:** Upgraded the main container with `backdrop-filter: blur(12px)` and a holographic border-pulse animation.
- **Mobile Readability:** Applied `word-break: break-all` to alert messages to ensure raw verification tokens do not overflow on small screens.

### Fixed
- **Mobile Scrolling:** Optimized `overflow-y` properties to ensure a smooth user experience on touch-based mobile browsers.
