# Simple HLS Manifest Viewer 👀

Hello👋

This is a simple and basic browser-based tool for viewing and analyzing HLS (HTTP Live Streaming) playlist manifests. No installation required - just open and use!

![alt text](image-1.png)

## What does it do? 🤔

This tool makes it super easy to inspect HLS stream manifests. Just paste your master manifest URL, and it will fetch and display:
- The master manifest
- All video variant playlists
- All audio playlists
- All subtitle/caption playlists

Each manifest is displayed in a separate tab with helpful metrics like:
- Total duration
- Segment count
- Number of discontinuities
- Number of ad breaks (cue-outs)
- Media sequence numbers
- Discontinuity sequence numbers

### Key Features ✨

- **No Installation Required**: Just open index.html in your browser
- **History**: Keep track of recently viewed manifests
- **Smart Selection**: Select segments to see their combined duration
- **Divergent Sequence Detection**: Highlights mismatched media/discontinuity sequences
- **Copy Support**: Easy URL copying and manifest content selection

Instead of playing the stream in a video player and digging through browser network requests to find and inspect manifests, you can quickly view everything in one place. No more jumping between multiple network requests or manually calculating segment durations!

## Getting Started 🚀

1. Download or clone this repository
2. Open `index.html` in your web browser
3. Paste an HLS stream URL
4. Done! 🎉

That's it! No npm, no installation, no server required. All processing happens in your browser.

## Browser Support 🌐

Works in all modern browsers that support ES6+ JavaScript:
- Chrome
- Firefox
- Safari
- Edge

## Contributing 🤝

Feel free to open issues or submit pull requests if you have suggestions for improvements!