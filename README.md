# Roblox Bulk Leave Communities

A Chrome, Edge, Brave and Opera GX extension that lets you select and leave multiple Roblox communities (groups) at once.

## Features

- Lists all your communities with their icons and member counts
- Search, sort (A→Z, most or fewest members) and an "All / Selected" filter
- Click to select, Shift+click for ranges, keyboard navigation
- Confirmation step before anything is left
- Live per-community progress, a progress bar and a Stop button
- Communities you own are locked so you can't leave them by accident
- Handles Roblox rate limits automatically
- Opens from the toolbar icon or the floating button on roblox.com

## Install (Chrome / Edge / Brave / Opera GX)

1. Download or clone this repository.
2. Open your browser's extensions page:
   - Chrome: `chrome://extensions`
   - Edge: `edge://extensions`
   - Brave: `brave://extensions`
   - Opera GX: `opera://extensions`
3. Turn on **Developer mode** (a toggle at the top-right in Chrome, Edge and Brave, or at the top of the page in Opera GX).
4. Click **Load unpacked** and select the project folder.
5. Log in at [roblox.com](https://www.roblox.com) and reload the page.

**Opera GX tip:** to keep the toolbar button visible, click the puzzle-piece icon in the toolbar and pin the extension. The red floating button on roblox.com works either way.

## Usage

1. Click the toolbar icon, or the red button at the bottom-right of any Roblox page.
2. Select the communities you want to leave.
3. Click **Leave**, then confirm.

## Notes

- Leaving a community can't be undone by this extension. You'd have to rejoin manually.
- Some leaves may fail if Roblox requires extra verification. Failed ones stay in the list with the reason.
- The extension only talks to Roblox's own APIs using your existing logged-in session. It doesn't collect or send your data anywhere else.

## Disclaimer

This project isn't affiliated with, endorsed by, or sponsored by Roblox Corporation. Roblox is a trademark of Roblox Corporation. Use at your own risk.

## License

MIT, see [LICENSE](LICENSE).
