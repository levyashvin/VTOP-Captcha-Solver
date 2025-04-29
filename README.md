# VTOP Captcha Solver

This userscript automatically solves the **text-based captchas** used on the [VIT VTOP portal](https://vtop.vit.ac.in/vtop/).

VTOP uses **two types of captchas**:
- **Text-based CAPTCHA** — solved by this userscript
- **Google reCAPTCHA** — can be solved using the [Buster extension](#solving-google-captcha).

This script automatically detects, solves, and fills the text captcha field on the login page.

---

## Installation Instructions

You need a userscript manager installed in your browser to use this script.  
Choose any one of the following:

| Userscript Manager | Download Link |
|:-------------------|:--------------|
| **Violentmonkey** (Lightweight, recommended) | [Violentmonkey Download](https://violentmonkey.github.io/get-it/) |
| **Tampermonkey** | [Tampermonkey Download](https://www.tampermonkey.net/index.php) |
| **Greasemonkey** (for Firefox only) | [Greasemonkey Download](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) |

### Steps to install:

1. Install any one userscript manager from the above links.
2. After installation, create a **new userscript** in the manager.
3. Copy and paste the provided userscript code into it (code is in the .js file).
4. Save it.
5. Open [VTOP Login Page](https://vtop.vit.ac.in/vtop/).
6. The captcha field will now **auto-solve** whenever the page loads!

---

## Solving Google reCAPTCHA

If VTOP shows a **Google reCAPTCHA** instead of a text captcha,  
you can solve it easily using another extension called **Buster**.

| Extension | Download Link |
|:----------|:--------------|
| **Buster: Captcha Solver for Humans (Chrome)** | [Buster Chrome Web Store](https://chromewebstore.google.com/detail/buster-captcha-solver-for/mpbjkejclgfgadiemmefgebjfooflfhl?hl=en) |
| **Buster: Captcha Solver for Humans (Firefox)** | [Buster Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/buster-captcha-solver/) |

**How to use:**
- When a Google reCAPTCHA appears, click the **small Buster icon** under the challenge.
- Buster will attempt to automatically solve it (audio or visual challenge).
- After that, continue with login as normal.

---

## Notes

- This script only solves **text-based VTOP captchas**.
- For **Google reCAPTCHA**, Buster must be installed separately.
- The script adjusts the captcha image size internally for better OCR accuracy.

---

## Disclaimer
This script is provided for educational and personal use only.  
Please use responsibly and do not misuse automated login mechanisms on official websites.

---

# Credits
- Script logic and training dataset by [ViBoot](https://chromewebstore.google.com/detail/viboot/mhbflefepokengbccinkmfhokjkphbol?hl=en), [VITrendz](https://www.vitrendz.com/) (Chromium based browsers only).
- Thanks to [Buster](https://github.com/dessant/buster) for captcha solving extension.

---

# Quick Screenshot Example
*(add it later)*

