# Falcons Golf — Quail Hollow Middle School

A single-page site for the Charlotte Falcons golf team. No login, no app, no “CMS.” If you can edit a group text, you can update this.

## What’s in the folder

- `index.html` — the whole website (looks + schedule + news)
- `photos/` — team pictures. Keep the names the same, or add a new file and list it in the gallery.

Open `index.html` in a browser to preview on your computer.

## How to change things

1. Open `index.html` in any text editor (TextEdit, Notepad, VS Code).
2. Jump to the bottom. Look for the comments that say **EDIT ANNOUNCEMENTS HERE**, **EDIT SCHEDULE HERE**, or **EDIT GALLERY HERE**.
3. Copy one of the `{ ... }` blocks, paste it, and change the words.
4. Save. Refresh the browser.

### Coach name

Search the file for `EDIT COACH`. Change the line that says `TBD`.

### New photo

1. Save a `.jpg` into `photos/` (a phone photo is fine; a smaller copy loads faster).
2. Add a line in the `GALLERY` list, same shape as the others.

Schedule rows marked `status: "example"` show a small “Example” tag. After Coach Blackley confirms a date, change that to `status: "confirmed"` and fill in `result` after the match.

## Put it on the internet (free, GitHub Pages)

Takes about ten minutes.

1. Make a free account at [github.com](https://github.com) if you don’t have one.
2. Click **New repository**. Name it something like `falcons-golf`. Make it **Public**. Skip adding a README (we already have one).
3. Upload this folder: `index.html`, `README.md`, and the `photos` folder. They need to sit at the **root** of the repo (not inside another folder).
4. In the repo, open **Settings → Pages**.
5. Under **Build and deployment**, set Source to **Deploy from a branch**.
6. Branch: `main`, folder: `/ (root)`. Save.
7. Wait a minute. GitHub will show a URL like `https://YOURNAME.github.io/falcons-golf/`.

That link is the team site. Share it with families.

Anytime you change a file and upload it again, the live page updates.

## Notes

- Photos are of real players. Don’t add last names in captions.
- The sample schedule is a typical CMS middle-school golf window, not an official 2026 slate. Replace it.
