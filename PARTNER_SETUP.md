# W.W.W. Grand Prix overlay: setup for co-streamers

You don't download anything. Everything runs from two links.

## Your links
- **Overlay:** https://stillfy.github.io/WWW-Grand-Prix/www_overlay.html
- **Control panel:** https://stillfy.github.io/WWW-Grand-Prix/www_control.html

## 1. Add the overlay to OBS
1. In your scene: **+ → Browser**, name it `WWW Overlay`.
2. **URL:** paste the overlay link. For a different look, use one of these instead:
   - Minimal: https://stillfy.github.io/WWW-Grand-Prix/www_overlay.html?theme=min
   - Fighting-game bars: https://stillfy.github.io/WWW-Grand-Prix/www_overlay.html?theme=arc
   - Bottom ticker bar: https://stillfy.github.io/WWW-Grand-Prix/www_overlay.html?theme=bar
3. **Width 1920, Height 1080.** Tick **Control audio via OBS** (the sound effects are quiet).
4. Put it above your game capture.

## 2. Add the control panel (only if you're running the scores)
1. **Docks → Custom Browser Docks**, name it `WWW Control`, paste the control link, then **Apply**.
2. Your teams, records and settings save inside your own OBS. They are separate from STiLL's.
3. To get the latest teams and records: open the **TO Hub** (https://claude.ai/artifact/BewFDBTj8r28sgafrC9sio) → **Backfill & sync → Download panel file**. Then in your control panel go to **Bracket → Import backup**.

## Getting updates
Nothing to install. When STiLL posts an update, right-click the Browser Source → **Refresh**, and reload the dock. If it still looks old, open the source's **Properties → Refresh cache of current page**.

## Good to know
- Your overlay is driven by **your** control panel. It doesn't show STiLL's live scores, because each PC runs its own.
- Leave the 🔒 PIN and **Hotkeys ON/OFF** switches alone unless you need them. They stop accidental resets and key presses.
- If something gets reset by mistake: **Setup → 🛟 Safety backups → Restore**.
