# Vicious Download Manager

A fast download manager for Windows. Installers and updates are published on the Releases page: download the latest ViciousDM-Setup and run it. The app checks for new versions by itself.

## Features

### Downloads
- Multi-connection downloading: each file is split into up to 32 parallel segments.
- Pause and resume with byte-accurate continuation, including after a restart.
- Segment view showing the progress of each part.
- Queues with a limit on simultaneous downloads, start and stop times, and an option to shut down the PC when the queue finishes.
- Automatic fallback to a single stream when a server does not support byte ranges.
- Incognito downloads that leave no record in the history.
- Download categories with a separate save folder for each.

### Video and audio
- Download video from many websites, with a choice of quality.
- Extract audio only (MP3, M4A, FLAC, WAV).
- Streaming (HLS) links with size and remaining time estimates.

### Torrents
- Magnet links and .torrent files.
- Choose which files of a torrent to download.
- Tracker list management.

### Link Grabber
- Clipboard monitoring that picks up copied links and checks that they are available.
- Group links into packages and download them together.

### Browser extension
- Chrome, Edge, Brave and Opera GX are supported. Firefox is not supported yet.
- Takes over browser downloads and sends them to the app.
- Download button on web video players, with a choice of quality.
- Toolbar pop-up listing the streams found on the page and the latest downloads.
- Downloads the browser cannot hand over (for example pages behind a security check) stay with the browser.
- Excluded Sites: list websites the app should leave alone.
- Settings > Browser Integration shows the status of the extension in each browser and helps install or update it.

### Windows integration
- System tray with quick pause and resume.
- Option to start with Windows, hidden in the tray.
- Small pop-up windows for download info, progress and completion, which can be turned off individually.
- Notifications when a download completes.
- Hardware acceleration switch for older computers.

### Appearance
- Several themes and accent colours.

### Updates
- Checks for updates on its own and from Settings > About: download now, skip a version or decide later, with a progress bar and a cancel option.
- A red dot in Settings shows when an app update or a browser extension update is waiting.

## Installation

1. Download ViciousDM-Setup from the latest release and run it.
2. To use the browser extension, download the extension zip from the same release (or use the Install button in Settings > Browser Integration), turn on Developer mode on the browser's extensions page, and load the extension folder.
