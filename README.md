# Cathay Pacific — The Journey Continuity System (Concept Demo)

A single-page interactive mockup of what "The Journey Continuity System" could look like inside the Cathay Pacific mobile app. Built for HADM 3650 Assignment 5.

## What's inside
- `index.html` — the entire site in one file (HTML + CSS + JS). No build step, no dependencies.
- 12 interactive phone screens across four journey stages: Pre-Flight, At Airport, Inflight, Arrival.
- Click any tile/row inside the phone, use the arrow buttons, tap the stage tabs, or use the left/right arrow keys to move through the journey.

## How to host it on GitHub Pages

1. **Create a new GitHub repo** (public is easiest). Name it something like `cathay-journey-continuity` or `journey-continuity-demo`.
2. **Upload `index.html`** (and this README if you like) to the root of the repo. You can do this right in the GitHub web UI: *Add file → Upload files → drag `index.html` in → Commit changes*.
3. **Enable GitHub Pages**: go to the repo's *Settings → Pages*. Under *Source* pick **Deploy from a branch**, then choose **Branch: `main`** and folder **`/ (root)`**. Click *Save*.
4. **Wait about a minute**, then refresh the Pages settings page — you'll see a URL like `https://<your-username>.github.io/<repo-name>/`. That's your live demo.
5. (Optional) Generate a QR code for that URL — useful for the presentation hand-off moment described in the script.

## How to host it on Netlify Drop (no git required)

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag the folder containing `index.html` onto the page.
3. Netlify gives you an instant URL you can share.

## Customizing

- All text content is in `index.html`. Search for any passenger name, flight number, gate, or copy and edit in place — no rebuild needed.
- Brand colors live near the top of the `<style>` block as CSS custom properties (`--jade`, `--gold`, etc.). Change those to adjust the palette globally.
- To add a new screen, duplicate any `<section class="screen" data-stage="…" data-screen="…">` block and increment `data-screen`. The JavaScript picks it up automatically.

## Note
This is a student-built concept mockup and is not an official Cathay Pacific product. Brand references are used for academic purposes only.
