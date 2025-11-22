# Apology QR — Single-file webpage

This repository contains a single-page apology web app that you can host using GitHub Pages.

Files:
- index.html        (the apology webpage)
- assets/           (create this folder and add `song.mp3` or any other assets)

Quick deploy (local -> GitHub):
1. Create a new repo on GitHub (e.g., apology-qr).
2. Copy the files into the repo root and commit.
3. Add an `assets/` folder and place your song file as `assets/song.mp3`.
   - If you're using the uploaded file path from this session (video example), it's: `/mnt/data/VID_20251122_060533_822.mp4`
4. In the repository settings enable **GitHub Pages** from the main branch root.
5. Open: `https://<username>.github.io/<repo>/` and use `?scanned=1` to auto-trigger the reveal (e.g., `https://.../?scanned=1`).

Notes:
- The audio is referenced externally as `assets/song.mp3` (so the audio file is outside the HTML file as you requested).
- Mobile browsers may block autoplay; the page includes a tap-to-enable hint. If autoplay is blocked, the first touch will start the music.
