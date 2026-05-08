# 1.0.0

Welcome to the inaugural release of **zen-captcha-core**. This version establishes the baseline for futuristic, neon-soaked human verification without the headache of backend configuration.

---

### 🚀 What’s New
* **Pure Client-Side Logic**: Successfully proof your humanity using only HTML, CSS, and JavaScript—no PHP required for the initial gatekeeping.
* **Futuristic UI/UX**: Implemented a dark-themed, glassmorphic container featuring "Neon Cyan" accents and high-contrast verification buttons.
* **Responsive Architecture**: Added viewport scaling and flexbox centering to ensure the grid looks good on everything from a desktop to a handheld communicator.
* **Token Resilience (+ Word Wrap)**: Integrated `word-break: break-all` on the response output to ensure long reCAPTCHA tokens don't shatter the layout.
* **Custom Alert System**: Swapped boring browser alerts (`alert()`) for a themed "SECURITY BREACH" and "ACCESS GRANTED" overlay system.

---

### 🛠️ Technical Details
* **Core Engine**: Google reCAPTCHA v2 API.
* **Styling**: CSS Variables (`--neon-cyan`, `--dark-bg`) for easy theme tweaking.
* **Validation**: JavaScript-based `grecaptcha.getResponse()` check.

---

### ⚠️ Known Reality Checks
* This version utilizes **Client-Side Validation**. While it looks cool and stops basic bots, it does not verify the token on a server.
* Requires a valid Google reCAPTCHA Site Key to be inserted at line 125.

---

> "You proofed you are a human, now you are a human."
