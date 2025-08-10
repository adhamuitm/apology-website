# I Owe You an Apology — simple web app

A tiny client-side apology card you can customize and share via link.

## How to use
1. Edit fields on the left. Live preview updates on the right.
2. Click "Create link" to encode the card in the URL. The link is copied to your clipboard.
3. Paste the link into a message to share.

## Deploy on GitHub Pages
1. Create a new GitHub repo (e.g. `sorry-for-us`).
2. Add `index.html`, `style.css`, `script.js`, and this `README.md`.
3. Commit and push.
4. In the repo settings, enable GitHub Pages from the `main` branch (root).
5. Open `https://<your-username>.github.io/sorry-for-us` and share.

## Customization
- Change colors in `style.css`.
- Replace copy/alerts with nicer modals if you want.
- To prefill the page from another source, append query params: `?n=Name&m=...&r=...&p=...&img=dataURI`

## Notes
- All work is client-side. Photos are encoded in the URL (data URI), so avoid very large images.
- Keep messages honest and personal; the app only helps present them well.
