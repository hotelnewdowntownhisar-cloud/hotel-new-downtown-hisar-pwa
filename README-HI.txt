HOTEL NEW DOWNTOWN HISAR — PWA WRAPPER

This package is an installable PWA shell around your existing Google Apps Script web app.
It does NOT replace Code.gs or Index.html and does not change Google Sheet data.

Hosting required:
- Upload these files to an HTTPS static host (for example GitHub Pages or Firebase Hosting).
- Install the PWA from that HTTPS hosting URL, not from script.google.com.
- Your existing Apps Script URL is embedded in index.html.
- Login and hotel data remain in Apps Script / Google Sheet.
- Only the app shell is cached. Login, booking, billing, reports and all data require internet.

Files: index.html, manifest.webmanifest, sw.js, icons/icon-192.png, icons/icon-512.png

Configured Apps Script URL:
https://script.google.com/macros/s/AKfycbwDuY33SR0R9ehycekiYEW0XjVX422ow4a1F934QY1KlnTLNmvgZRuuhvgny5ouqWSR/exec

After hosting:
1. Open the HTTPS site URL in Android Chrome.
2. Tap ⋮ > Install app (or Add to Home screen).
3. Confirm Install.
4. Open the installed Hotel New Downtown Hisar icon.

Note: Google sign-in / Apps Script may be blocked inside an iframe on some devices due to
Google account or third-party-cookie restrictions. If that happens, use the direct Apps Script
URL in Chrome with Add to Home screen instead, or we can switch to a non-iframe integration.
