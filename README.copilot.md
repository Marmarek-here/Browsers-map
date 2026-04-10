# Copilot Changes Log

Format: [Date] [Time EEST] - [Summary]

## 2026-04-10

- 15:25 - Removed duplicate blue description box in sidebar. Files: index.html.
- 15:25 - Added/migrated many logos to higher resolution sources. Files: data.json.
- 15:25 - Added author field and rendered it in sidebar details. Files: data.json, index.html.
- 15:25 - Compacted tree spacing and hid Ungoogled icon on map node (kept in sidebar). Files: index.html.
- 15:25 - Added sidebar animation and dark/light theme support. Files: index.html.
- 15:58 - Added currentVersion/eol to all nodes + auto-fill fallback; fixed runtime JS syntax issue. Files: data.json, index.html.
- 16:02 - Improved light-theme contrast and graph text/edge theming; fixed theme control overlap; refined close animation. Files: index.html.
- 16:14 - Fixed key icon URLs; made tip one-time; removed emoji labels; switched to theme dropdown; made sidebar reveal immediate. Files: data.json, index.html.
- 16:40 - Switched icons to Google Favicons API; verified exact versions for major browsers; added responsive layout, legend filtering, Presto/Mosaic colors, Netscape lineage update, WebView2 reposition, and themed Suggest button. Files: data.json, index.html.
- 16:47 - Added `versionSource` to all nodes; upgraded icon fetching with fallback; improved mobile layout stability. Files: data.json, index.html.
- 17:29 - Finalized fun-mode with cleanup; improved mobile layout and faviconV2 pipeline. Files: index.html.
- 17:33 - Removed Fun button and all fun-mode code; added collapsible legend on mobile; improved mobile layout consistency; added bottom-right watermark "Browsers tree by Marmarek". Files: index.html.
- 17:40 - Fixed watermark hidden by sidebar (moved to bottom-center, fades when sidebar open); added LOGO_OVERRIDES for Firefox (distinct fox icon), Chromium, Ungoogled Chromium (GitHub avatar), Netscape Navigator, NetSurf (high-res Wikimedia SVGs/PNGs instead of low-res favicon API). Files: index.html.
- 18:28 - Added Thorium node (derived from Chromium) + edge; switched map cursor to global custom circle on desktop (legend/sidebar included); updated NetSurf logo to official repo asset and IceCat to GNU image in data/overrides. Files: data.json, index.html.
- 18:44 - Fixed light-mode custom cursor visibility; switched Thorium to noWiki custom description; hid Wikipedia link when no target exists. Files: data.json, index.html.
- 19:08 - Added Floorp (Firefox family), IceWeasel->IceCat lineage, and Basilisk from Pale Moon; updated Gecko color/legend/label/meta mappings. Files: data.json, index.html.
- 19:10 - Added Helium/Yandex (Chromium family) and Comet from Arc; updated Blink mappings. Files: data.json, index.html.
- 19:33 - Improved map readability: node click highlights ancestors (amber), descendants (cyan), and dims unrelated branches; background tap clears focus. Files: index.html.
- 19:36 - Added Goanna from Gecko; Pale Moon/Basilisk now from Goanna; moved Helium to WebKit lineage; updated mappings. Files: data.json, index.html.
- 19:44 - Removed click-focus effect; added pink Goanna legend family/mapping (Goanna, Pale Moon, Basilisk). Files: index.html.
- 19:52 - Sidebar closes on empty-space clicks inside its container. Files: index.html.
- 20:25 - IceCat directly from Firefox; consumer Chromium browsers (Brave, Edge, Opera, Vivaldi, Arc, Kiwi, Samsung, Yandex) moved under Chrome for tree cascade. Files: data.json.

Notes:
- Compressed format maintained to stay under size cap.
