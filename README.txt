AX EDITZ Android PWA starter

Upload all files in this folder to the ROOT of the GitHub Pages repository that serves https://vikram635.github.io/Vik/. Keep index.html, manifest.json, sw.js, and icon.svg in the same folder.

IMPORTANT LIMITATIONS: This package caches the app shell for repeat/offline opening only. It does NOT make Supabase login/signup work offline, and it does not prove video export works offline on every Android browser. The existing editor uses browser MediaRecorder/canvas APIs and should be tested on the target phone. The original HTML has a save/load-project UI; its persistence implementation still needs device testing. This is a PWA starter, not a signed Android App Bundle (.aab). PWABuilder/TWA packaging and Play Console checks are still required.
