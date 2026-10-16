Postal History Album Editor V6 — Safari deployment package

GitHub Pages setup:
1. Create a PUBLIC repository named postal-history-editor (never upload personal scans or saved project JSON files).
2. Upload the six files from this ZIP to the root of the repository.
3. Settings > Pages > Deploy from a branch > main / (root) > Save.
4. Open https://YOUR-GITHUB-USERNAME.github.io/postal-history-editor/ in Safari.
5. Share > Add to Home Screen.

The website's code is public. Scans selected through the file picker are processed in the browser and are not deliberately uploaded to the hosting server. Export uses third-party JavaScript loaded from cdnjs; PDF import also loads PDF.js from cdnjs. A network connection is required for these libraries unless already cached.

Export A4 PDF generates a rasterized page (not vector text), so check quality and scale before exhibition use. Save project uses browser download and may work better in Safari than Files preview. Print uses browser printing. No cloud sync, authentication, or server-side storage is provided. Existing V4.1 project files can be opened.

The code is a prototype and has not been tested on physical iPad Safari.
