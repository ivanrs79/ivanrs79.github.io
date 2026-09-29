# ivanrs79.github.io

Root GitHub Pages site. It exists mainly to serve domain-level files that must live at the root of `ivanrs79.github.io`:

- `.well-known/assetlinks.json`: Android Digital Asset Links for the **2048 Stone Clash Multiplayer** app (`io.github.ivanrs79.game2048`). Lets the app open full-screen and handle `https://ivanrs79.github.io/2048/...` links.
- (later) `.well-known/apple-app-site-association` for iOS Universal Links.

`.nojekyll` makes GitHub Pages serve the `.well-known` folder. The root page redirects to the game at [/2048/](https://ivanrs79.github.io/2048/).