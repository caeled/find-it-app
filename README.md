# Find It — desktop app

The standalone desktop version of **Find It**, the traveler app from Steven Powell's Everyday Cool collection: tap a big category button (coffee, pharmacy, hospital, gas, groceries, and more), and Find It shows what's near you on a map, sorted by distance, with directions for each place. Use "Find me" or type a ZIP code or town.

Find It is a Tauri v2 shell around the project's web page (`dist/`). It needs an internet connection: maps and place data come from OpenStreetMap contributors via the Overpass API and Nominatim, and the map tiles and Leaflet library load from their public servers. Places' own website and social links, when the map data carries them, open in your default browser.

## Installers

Built by GitHub Actions on each `v*` tag and attached to the GitHub release:

- Windows: `Find.It_<version>_x64-setup.exe` (or the `.msi`)
- macOS: `Find.It_<version>_universal.dmg` (Intel and Apple silicon)

The builds are unsigned, so Windows SmartScreen or macOS Gatekeeper may ask you to confirm before the first run.

## The web version

The same Find It lives in the Everyday Cool collection at https://caeled.github.io/everyday-cool/projects/find-it/ — the desktop app and the page are the same code.

## License

MIT for the code; see `dist/LICENSE-CONTENT.md` for the artwork and text. Map data © OpenStreetMap contributors (ODbL); see `dist/THIRD-PARTY.md`.
