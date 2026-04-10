# Browsers Tree

An interactive visualization of web browser genealogy and engine relationships.

## Features

- Interactive node-based graph showing browser lineages
- Click on any browser or engine to see details from Wikipedia
- Smooth zooming and panning
- Color-coded by rendering engine:
  - 🔵 Chromium-based (Blink)
  - 🟣 Gecko-based (Firefox)
  - 🟢 WebKit-based
  - 🟠 Independent engines
  - ⚪ Legacy engines

## How to Use

- **Zoom**: Scroll to zoom in/out smoothly
- **Pan**: Drag to move around the map
- **Details**: Click on any node to view information in the sidebar
- **Close**: Click outside or the ✕ button to close details

## Browser Lineages

- **Chromium/Blink**: The most widely used engine, forked from WebKit. Powers Chrome, Edge, Brave, Opera, Vivaldi, Arc, Kiwi, Min, Samsung Internet, Android WebView, and many others
- **Gecko**: Firefox's engine, also used by Tor Browser, LibreWolf, Mullvad, Pale Moon, Zen, GNU IceCat, Waterfox
- **WebKit**: Originally from KHTML (Konqueror), powers Safari, iOS WKWebView, macOS WebView
- **Trident/EdgeHTML**: Microsoft's engines for Internet Explorer, legacy Edge, and Windows WebBrowser control
- **Presto**: Opera's former engine, used in older versions of Opera
- **Independent**: Engines like NetSurf, Dillo, Ladybird, etc.

## Technologies Used
- [Cytoscape.js](https://js.cytoscape.org/) for graph visualization
- Wikipedia API for browser descriptions
- Google Favicon API for logos

## Contributing

Found a missing browser or incorrect lineage? [Open an issue](https://github.com/Marmarek-here/Browsers-tree/issues) or submit a pull request!

## License

This project is open source. Feel free to use and modify.
