# 🦖 Project Nedry: The Ultimate Access Control System

> *"God dammit, I hate this hacker crap!"* — Ray Arnold

![Security Status](https://img.shields.io/badge/Security_Level-CRITICAL-red?style=for-the-badge) ![Status](https://img.shields.io/badge/System-LOCKED-red?style=for-the-badge) ![Magic Word](https://img.shields.io/badge/Magic_Word-NOT_SAID-yellow?style=for-the-badge)

## ⛔ What is this?

This is a **high-security honeypot** (read: a troll page) designed to catch unauthorized visitors, bots, and script kiddies who try to access my server via its raw IP address.

Instead of giving them a boring `403 Forbidden` or `404 Not Found`, we give them the full **Jurassic Park experience**.

## 🧠 The "Autoplay Bypass" Logic

Modern browsers (Chrome, Safari, Edge) block audio from playing automatically. This ruins the classic "Nedry" prank because the intruder never hears the magic word.

**Project Nedry solves this with social engineering:**
1.  **The Trap:** The user lands on a terrifying "SECURITY BREACH" screen.
2.  **The Bait:** A large, red `> UNLOCK SYSTEM <` button tempts them to fix the error.
3.  **The Switch:** Clicking the button counts as "user interaction," which legally authorizes the browser to play audio.
4.  **The Result:** The screen vanishes, and Dennis Nedry loops at 100% volume.

## 🚀 Deployment

### 1. Host it (You are here)
This repo is hosted via GitHub Pages.
* **Live URL:** `https://[YOUR-USERNAME].github.io/access-denied/`

### 2. Configure Nginx Proxy Manager
This project is designed to be the "Default Site" for Nginx Proxy Manager (NPM).

1.  Go to **NPM Dashboard** > **Settings** > **Default Site**.
2.  Select **Redirect**.
3.  **Forward Host:** `https://[YOUR-USERNAME].github.io/access-denied/`
4.  **Preserve Path:** `OFF` (Unchecked).
5.  **Save.**

Now, anyone hitting your raw IP or an unknown domain gets sent to the park.

## 📂 Files

* `index.html` - The trap interface and logic.
* `magic_word.mp3` - The audio payload (Ah, ah, ah!).
* `nedry.gif` - The visual payload.

## ⚠️ Disclaimer

I am not responsible for any frustration, broken keyboards, or sudden urges to steal dinosaur embryos caused by this page.

> *"Hold on to your butts."*
