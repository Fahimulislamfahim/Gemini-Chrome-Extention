# Gemini Side Panel Chrome Extension

A Chrome extension that opens Google Gemini in a convenient side panel with a single click.

## Features

- 🚀 Quick access to Google Gemini from any Chrome tab
- 📌 Persistent side panel that stays open while browsing
- 💬 Full Gemini interface embedded in the browser
- 🎯 Clean and simple one-click activation

## Installation

1. Open Chrome and navigate to `chrome://extensions/`
2. Enable **Developer mode** (toggle in the top-right corner)
3. Click **Load unpacked**
4. Select the `Web Chat` folder from this project
5. The Gemini Side Panel extension will appear in your extensions list

## Usage

1. Click the Gemini extension icon in your Chrome toolbar
2. The side panel will open on the right side of your browser
3. Gemini will load automatically in the panel
4. Start chatting!

## Files Structure

```
Web Chat/
├── manifest.json       # Extension configuration
├── sidepanel.html      # Side panel UI that loads Gemini
├── background.js       # Service worker for handling clicks
├── icon16.svg          # Extension icon (16x16)
├── icon48.svg          # Extension icon (48x48)
├── icon128.svg         # Extension icon (128x128)
└── README.md          # This file
```

## Technical Details

- **Manifest Version**: 3 (latest Chrome extension standard)
- **Permissions**: sidePanel
- **Target URL**: https://gemini.google.com

## Notes

- You need a Google account to use Gemini
- The extension simply embeds the Gemini web interface
- Internet connection required

## Troubleshooting

**Side panel doesn't open:**

- Make sure you're using Chrome 114 or later (side panel API requirement)
- Try disabling and re-enabling the extension

**Gemini doesn't load:**

- Check your internet connection
- Make sure you can access https://gemini.google.com in a regular tab
- Try refreshing the side panel

## License

Free to use and modify.
