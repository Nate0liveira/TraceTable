TraceTable
==========

Files:
- index.html: main app
- manifest.webmanifest: Home Screen/PWA metadata
- sw.js: offline cache
- icon-192.png / icon-512.png: app icons

GitHub Pages:
1. Upload all files to the repository root (or your Pages folder).
2. Enable GitHub Pages.
3. Open the HTTPS Pages URL in Safari on iPad/iPhone.
4. Use Share -> Add to Home Screen.
5. Add an image, position it, adjust the controls, then tap Lock for Tracing.

Important iOS note:
The app cannot directly set the iPad/iPhone hardware brightness. Manually set display brightness high in Control Center. The app uses a white maximum-light background and requests Screen Wake Lock when tracing is locked, where iOS permits it.
