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
- Only shows up on the [Roblox communities page](https://www.roblox.com/communities), so it stays out of your way everywhere else
- Opens from the toolbar icon or the floating button on that page

## Install (Chrome / Edge / Brave / Opera GX)

1. Download or clone this repository.
2. Open your browser's extensions page:
   - Chrome: `chrome://extensions`
   - Edge: `edge://extensions`
   - Brave: `brave://extensions`
   - Opera GX: `opera://extensions`
3. Turn on **Developer mode** (a toggle at the top-right in Chrome, Edge and Brave, or at the top of the page in Opera GX).
4. Click **Load unpacked** and select the project folder.
5. Log in at [roblox.com](https://www.roblox.com), then go to the communities page: https://www.roblox.com/communities (reload it if it was already open).

**Opera GX tip:** to keep the toolbar button visible, click the puzzle-piece icon in the toolbar and pin the extension. The red floating button on the communities page works either way.

## Usage

1. Go to https://www.roblox.com/communities.
2. Click the red button at the bottom-right of the page, or the extension's toolbar icon. (If you click the toolbar icon on another Roblox page, it takes you to the communities page first.)
3. Select the communities you want to leave.
4. Click **Leave**, then confirm.

## Notes

- Leaving a community can't be undone by this extension. You'd have to rejoin manually.
- Some leaves may fail if Roblox requires extra verification. Failed ones stay in the list with the reason.
- The extension only talks to Roblox's own APIs using your existing logged-in session. It doesn't collect or send your data anywhere else.

## Disclaimer

This project isn't affiliated with, endorsed by, or sponsored by Roblox Corporation. Roblox is a trademark of Roblox Corporation. Use at your own risk.

## License

MIT, see [LICENSE](LICENSE).
