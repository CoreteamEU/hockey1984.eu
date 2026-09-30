# Hockey 1984

Promotional website for Hockey 1984. Plain HTML and CSS, with no build step or dependencies.

## Publishing

Publish through GitHub Pages from the `main` branch, `/` (root), matching the morebands.eu setup.

- Website: https://hockey1984.eu/
- Repository: https://github.com/CoreteamEU/hockey1984.eu

The first version includes a game introduction, gameplay screenshot, instructions, and the verified App Store link. Android availability is not yet linked.

## Privacy notice

`privacy.html` is the app's privacy notice, moved unchanged in wording from https://coreteameu.github.io/hockeyScenes/privacy.html (Termly-generated, last updated February 01, 2021) and restyled for this site. Section anchors keep their original IDs. The old `hockeyScenes` site must stay online because the game downloads its scene files from it.

## Assets

Images are unmodified copies from the Hockey 1984 game project:

- `img/gameplay.jpg`: `android/app/src/main/play/listings/en-US/graphics/phone-screenshots/2.jpg`
- `img/logo.png`: `ios/HokejsSwift/Assets.xcassets/logo_eng.imageset/logo_eng.png`

Copy is based on that project's English store descriptions. App Store: https://apps.apple.com/app/id1533790213.

## Custom domain

GitHub Pages uses `hockey1984.eu` as its custom domain. Keep the root `CNAME` file committed.

DNS is managed at Zone using its existing nameservers. The apex uses GitHub Pages A records `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, and `185.199.111.153`. The `www` CNAME points to `coreteameu.github.io.`. GitHub manages the HTTPS certificate.
