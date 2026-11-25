# Cross Country Stars — iPhone Web App

This version is designed for Windows + iPhone without Xcode.

## What it does
- Opens as a standalone, app-style web app when added to the iPhone Home Screen.
- Uses fullscreen display when supported.
- Includes an offline service worker so the game can continue working after it has been cached.
- Keeps the original game HTML/JavaScript.

## Easiest way to put it on your iPhone
You need to host this folder at an HTTPS URL. GitHub Pages is a simple free option.

1. Create a GitHub repository.
2. Upload every file in this folder (`index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg`).
3. Turn on GitHub Pages for the repository.
4. Open the resulting HTTPS page on your iPhone in Safari.
5. Tap Share → Add to Home Screen → Add.
6. Launch "Cross Country Stars" from the Home Screen.

The first time, leave the game open long enough for the service worker to cache the files.

## Important
A PWA cannot be installed on iPhone by simply opening the HTML file from Files. It needs to be served from a web address, preferably HTTPS.
