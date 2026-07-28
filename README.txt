RENATO BIBOLOTTI ARCHIVES

Files:
- index.html
- style.css
- script.js
- assets/face.png
- assets/background-1.png
- assets/background-2.png

Animation timing:
- Background 1: 1 second
- Background 2: 1 second
- Complete background loop: 2 seconds
- Face half-turn: 1 second
- Face complete turn back to the original position: 2 seconds

The three buttons are interactive but intentionally do not open links yet.

To publish with GitHub Pages:
1. Upload every file and the assets folder to the root of your repository.
2. In GitHub, open Settings > Pages.
3. Choose the main branch and the root folder.
4. Save.


FAVICON AND LINK PREVIEW
- The browser tab icon uses assets/favicon.ico.
- The WhatsApp/social preview uses assets/social-preview.png.
- For the most reliable WhatsApp preview, after publishing replace:
  content="assets/social-preview.png"
  with the full public URL, for example:
  content="https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/assets/social-preview.png"
  in both og:image and twitter:image inside index.html.
- WhatsApp may cache an older preview for a while after an update.
