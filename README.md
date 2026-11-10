# W.W.W. Grand Prix: overlay & control panel

Hosted with GitHub Pages from **github.com/STiLLFY/WWW-Grand-Prix**.

## Links
| What | Link |
| --- | --- |
| Start page | https://stillfy.github.io/WWW-Grand-Prix/ |
| Overlay (OBS Browser Source) | https://stillfy.github.io/WWW-Grand-Prix/www_overlay.html |
| Control panel (OBS dock) | https://stillfy.github.io/WWW-Grand-Prix/www_control.html |

Overlay styles: add `?theme=min`, `?theme=arc` or `?theme=bar` to the overlay link. Leave it off for the full Grand Prix look.

## First-time setup (STiLL's PC)
1. **Settings → Pages** in this repo: Source *Deploy from a branch*, Branch `main` / `(root)`, leave Custom domain blank, then **Save**.
2. **Move your saved data before switching:** in the control panel you use now, go to **Bracket → Export backup**. Open the new control link, then **Bracket → Import backup**.
3. In OBS, point the overlay Browser Source and the custom dock at the links above.

## Updating
1. **Add file → Upload files** in this repo. Drag in the new `www_overlay.html` / `www_control.html` (same names), then **Commit changes**.
2. Wait about a minute. In OBS: right-click the Browser Source → **Refresh**, and reload the dock.
   Still old? Open the source's **Properties → Refresh cache of current page**.

Anyone using these links gets the update the same way. Nobody needs new files.

## Rules for extra hands
- Set a **🔒 PIN** in the control panel's top bar. Resets, deletes, merges, imports and restores need it. Scores, lives and wins don't.
- Turn **Hotkeys OFF** in the top bar when someone new is at the keyboard.
- Every reset or delete takes a safety backup first: **Setup → 🛟 Safety backups → Restore**.
- Off-stream results go in **Bracket → Off-stream result**, or in the TO Hub (then sync).

## TO Hub (shared records)
https://claude.ai/artifact/BewFDBTj8r28sgafrC9sio
- **Hub → panel:** Hub **Backfill & sync → Download panel file**, then in the control panel **Bracket → Import backup**.
- **Panel → Hub:** control panel **Bracket → Export backup**, then in the Hub **Backfill & sync → From the stream panel**.

Importing the same file twice never double-counts.
