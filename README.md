# EPM XXV — Free Artist Website

A responsive, dark cinematic red-and-black artist website made with plain HTML, CSS and JavaScript. Intended for free GitHub Pages hosting.

## Files
- `index.html` — the complete website
- `assets/images/hero.jpg` — optional hero portrait
- `assets/images/cover.jpg` — optional release artwork
- `assets/images/photo-01.jpg` through `photo-06.jpg` — gallery photos
- `assets/music/track-01.mp3` — optional MP3 for the built-in audio player

## Customize before publishing
1. Replace the placeholder YouTube video IDs `VIDEO_ID` and `VIDEO_ID_2` in `index.html`.
2. Replace the example YouTube, Spotify, Apple Music and Instagram links with your actual profile/release links.
3. In the script near the bottom, change `CONTACT_EMAIL` from `your-email@example.com` to your real email address.
4. Replace the biography and track title with your own details.
5. Upload your own photos using the exact filenames above. Use JPG, PNG or WebP, and keep files reasonably small for faster loading.
6. Upload your own MP3 to `assets/music/track-01.mp3` if you want the on-page player to work. Only upload music you own or have permission to publish.

## Publish for free with GitHub Pages
1. Sign in at https://github.com/ and create a **public** repository named `YOUR-USERNAME.github.io` (replace `YOUR-USERNAME` with your GitHub username).
2. Upload `index.html` and the `assets` folder to the root of the repository. You can upload the files from a Mac browser; GitHub's mobile website may be easier for small edits than bulk uploads.
3. Open repository **Settings → Pages**.
4. Under build and deployment, select **Deploy from a branch**; choose branch `main` and folder `/ (root)`, then Save.
5. Wait for the deployment to finish. Open `https://YOUR-USERNAME.github.io`.
6. Whenever you change files and commit the changes, GitHub Pages republishes the site.

## Free-plan notes
- GitHub Pages hosts static files. This site does not need a paid server.
- The contact form opens the visitor's email app; it does not send messages directly from the site.
- YouTube embeds require a real video ID. Spotify buttons are ordinary links; you can optionally replace them with Spotify embed players.
- No custom domain is required. A custom `.com` domain usually costs money.
