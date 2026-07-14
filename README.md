# Happy Birthday, Sia

A standalone, cinematic interactive birthday site for Sia's 17th birthday on July 20, 2026. Open `index.html` in a modern browser; there is no build step.

## Personalize it

- Replace the two commented audio file paths in `index.html` with licensed MP3s at `assets/music/soft-piano.mp3` and `assets/music/celebration.mp3`.
- Your three personal gallery images are now stored in `assets/images/`. To change them later, update both `src` and `data-full` for the relevant gallery entry in `index.html`.
- The date is set in `js/countdown.js`; update it if the celebration date changes.
- The birthday message is in `js/typing.js`.

## Features

The site includes a canvas night sky and fireworks, adaptive countdown, SVG cake with 17 extinguishable candles, optional microphone-based blow detection with a touch-friendly fallback, confetti, lightbox gallery, smooth scrolling, lazy images, keyboard-compatible buttons, and reduced-motion support.

## Notes

Microphone access needs HTTPS or `localhost` in most browsers. If it is unavailable or denied, clicking the candle button again automatically starts the celebration. Empty asset folders are intentional placeholders for private images, music, sounds, fonts, and icons.

## Put it on a phone with GitHub Pages

The site must be hosted before it can be opened on a phone. This project is prepared for GitHub Pages:

1. Create a new GitHub repository, for example `happy-birthday-sia`.
2. Upload every file and folder from this project to that repository (do not upload the containing folder itself).
3. In the GitHub repository, open **Settings → Pages**. Under **Build and deployment**, choose **GitHub Actions** as the source.
4. Open the **Actions** tab and wait for **Publish birthday site to GitHub Pages** to finish.
5. The completed action shows the shareable HTTPS page address. Open it on the phone.

HTTPS is important: it allows the optional microphone candle interaction to work on supported mobile browsers.
