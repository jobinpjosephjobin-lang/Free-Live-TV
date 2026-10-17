StreamDeck IPTV Player

Files:
- index.html: standalone webpage

Run locally:
1. Extract the ZIP.
2. Open index.html in a modern browser.
3. Paste a direct HTTP/HTTPS stream URL, or import an .m3u/.m3u8 playlist.

For GitHub Pages:
1. Create a GitHub repository.
2. Upload index.html to the repository root.
3. In Settings > Pages, enable deployment from the main branch and root folder.
4. Open the Pages URL GitHub provides.

Notes:
- HLS playback uses hls.js from jsDelivr CDN.
- Browser playback depends on stream format, CORS policy, authentication, and codecs.
- Loading a playlist from a remote URL requires that server to allow cross-origin fetches; importing a downloaded playlist works around that fetch restriction.
- The page does not include or provide any TV channels.
