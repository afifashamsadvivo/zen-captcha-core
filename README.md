# zen-captcha-core

### "Look at me. I am the human now."

`zen-captcha-core` is a lightweight, frontend-only verification gateway. It uses Google reCAPTCHA v2 to filter out the toasters and verify that your visitors are, in fact, carbon-based lifeforms with basic pattern recognition skills.

---

## ✨ Features

* **Zero Backend Required**: No PHP? No problem. This runs purely on HTML, CSS, and some very hardworking JavaScript.
* **Aesthetic Overload**: Features a futuristic "Neon Cyan" and "Dark BG" theme with glassmorphism effects.
* **Device Agnostic**: Fully responsive and mobile-ready, utilizing flexbox and viewport scaling to work on all devices.
* **Token Word-Wrap**: Includes `word-break: break-all` logic so those massive reCAPTCHA tokens don't break your layout.
* **Custom Alert System**: Replaces boring browser alerts with a themed "Futuristic Verification" overlay.

---

## 🚀 How to Use

1.  **Download:** Head over to the [Releases](https://github.com/afifashamsadvivo/zen-captcha-core/releases "The releases tab") tab and pick your favorite flavor of digital poison (aka the HTML file). We’re currently rocking semantic versioning, but we’ll be switching to CalVer after 1.0.0 because, much like a robot trying to identify a crosswalk, we have no concept of linear time
2.  **Get a Key**: Grab your `sitekey` from the Google reCAPTCHA Admin Console.
3.  **Insert the Key**: Find the following line in the code and swap it for your actual key:
    ```html
    <div class="g-recaptcha" data-sitekey="YOUR_RECAPTCHA_ADMIN_SITE_KEY"></div>
    ```
4.  **Profit**: Open the file and start gatekeeping your content like a futuristic bouncer.

---

## ⚠️ The "Honest Peer" Disclaimer

This system provides **Client-Side Validation**. While it stops 99% of casual bots and looks incredibly cool doing it, a particularly smart robot (or a human who knows how to use the browser console) could technically bypass the visual alert. 

If you are protecting something high-stakes, remember that true security usually involves a server-side check. If you're just making a cool landing page or a personal project, you're golden.

---

> "Verification required. Please solve the puzzle first... or just stay a robot, I'm a README, not your boss."
