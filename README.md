# Cole Train Workout Coach (Build 001)

A free, local-first Android-friendly web app prototype.

## What's included
- Spoken coach output using the browser's built-in speech synthesis
- Optional microphone commands where browser speech recognition is supported
- Local workout logging and history (saved in this browser on this device)
- Rest timers
- Five coaching modes
- Daily challenge rotation
- Original synthesized sound effects and a simple generated beat
- Installable PWA shell

## Run it on Android
1. Extract this folder.
2. Put the three files on a static HTTPS host (GitHub Pages is a free option) or run a local web server on your computer.
3. Open the HTTPS site in Chrome on Android.
4. Grant microphone permission if prompted.
5. Chrome menu (three dots) > Add to Home screen / Install app.

Speech recognition support varies by browser and device. If the microphone button is unavailable, the app still works with buttons and spoken output.

## Free hosting with GitHub Pages
1. Create a free GitHub account and a new public repository named `cole-train-coach`.
2. Upload `index.html`, `manifest.json`, and `sw.js` to the repository root.
3. Open repository Settings > Pages.
4. Under Build and deployment, select Deploy from a branch, choose `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish. Open the provided HTTPS address on your Android phone.

## Privacy and limits
- No API key, paid service, or server is used.
- Workout records stay in browser localStorage. Clearing site data can erase them.
- Browser speech voices are not Cole's original game voice. Use only authorized voice recordings/voice models if upgrading.
- The generated beat and tones are original synthesized sounds, not Gears of War music.
- This prototype does not automatically count reps or run in the background reliably when Android suspends the browser.

## Next build
Add optional export/import backup, more robust workout templates, a proper background timer/notification strategy, and a server-backed account only if you later choose to pay for hosting/services.
