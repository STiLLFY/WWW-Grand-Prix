# W.W.W. Grand Prix: hosted overlay

Upload everything in this folder to one GitHub repository and turn on GitHub Pages.
From then on, an update means uploading the new `www_overlay.html` and `www_control.html` over the old ones; every OBS that points at the links gets it on refresh.

## One-time setup (about 10 minutes)
1. Make a free account at github.com, then **New repository** → name it `www-grand-prix` → Public → Create.
2. **Add file → Upload files** → drag in all files from this folder → Commit.
3. **Settings → Pages** → Source: *Deploy from a branch*, Branch: `main` / root → Save. Wait a minute.
4. Your links are now:
   - Control: `https://YOURNAME.github.io/www-grand-prix/www_control.html`
   - Overlay: `https://YOURNAME.github.io/www-grand-prix/www_overlay.html`
5. **Before switching, move your saved data:** open the OLD control panel → Bracket → **Export backup**. Open the NEW control link → Bracket → **Import backup**.
6. In OBS: point the Browser Source and the custom dock at the new links (replace the old file paths).

## Updating later
Upload the two new HTML files to the same repository (Add file → Upload files, same names). In OBS, right-click the Browser Source → *Refresh*, and reload the dock.

## Rules for extra hands
- Set a PIN with the 🔒 button in the control panel's top bar. Resets, deletes, merges, imports and restores need it; scores, lives and wins don't.
- Turn **Hotkeys OFF** in the top bar when someone new is at the keyboard.
- Every reset or delete takes a safety backup first. Setup → Safety backups → Restore undoes a mistake.
- Off-stream results go in Bracket → Off-stream result, or in the TO Hub (then Stream sync).
