# Arslonbek & Shaxnozaxon Wedding Invitation

A premium interactive wedding invitation page built with HTML, CSS, and vanilla JavaScript. It includes a modern landing cover, countdown, RSVP form, guestbook, theme switcher, music toggle, gift card section, and share/calendar actions.

## Features
- luxury invitation cover screen
- live countdown timer
- theme switcher (beige-gold, white-floral, burgundy-gold)
- background music toggle
- fallback WebAudio melody if `azizam.mp3` is missing
- share button and calendar download
- RSVP form and guestbook
- polished gift-card section for cash/gift support
- responsive layout

## Project structure
- `index.html` — main invitation page
- `MUSIQA_QOSHISH.txt` — installation guidance
- `.gitignore` — excludes local audio files and system files

## How to use
1. Put your real `azizam.mp3` file in this folder if you have one.
2. Open `index.html` in a browser.
3. Click “Taklifnomani ochish”.
4. Music starts automatically after interaction.

If the MP3 file is missing, the page uses a built-in browser melody so the invitation still works without errors.

## GitHub Pages deployment
1. Push the repository to GitHub.
2. Open repository settings.
3. Select Pages.
4. Set Source to `Deploy from a branch` and choose `main` + `/ (root)`.
5. Save.

## Notes
- The music file is intentionally not committed because it is binary and usually large.
- The invitation continues to work even if the audio file is absent thanks to the built-in fallback melody.

## License
MIT
