# Hockey 1984

Promotional website for Hockey 1984. Plain HTML and CSS, with no build step or dependencies.

## Publishing

Publish through GitHub Pages from the `main` branch, `/` (root), matching the morebands.eu setup.

- Website: https://hockey1984.eu/
- Repository: https://github.com/CoreteamEU/hockey1984.eu

The first version includes a game introduction, gameplay screenshot, instructions, and the verified App Store link. Android availability is not yet linked.

## Privacy notice

`privacy.html` is the privacy notice for the iOS and Android apps and the URL used in App Store
Connect and Google Play Console. Rewritten on 2026-09-30 from the 2021 Termly notice to disclose the
Google Mobile Ads SDK (per Google's Play data disclosure page), UMP consent, iOS App Tracking
Transparency, Game Center and the iOS level download from GitHub Pages; it must stay consistent
with the Play Data safety answers recorded in the game repo's `docs/android-release.md`. Anchors
`infocollect`, `infoshare`, `intltransfers`, `3pwebsites`, `inforetain`, `privacyrights`,
`policyupdates` and `contact` were kept; `DNT`, `caresidents` and `request` were removed. The old
`hockeyScenes` site must stay online because the iOS game downloads its scene files from it.

## Assets

Images are unmodified copies from the Hockey 1984 game project:

- `img/gameplay.jpg`: `android/app/src/main/play/listings/en-US/graphics/phone-screenshots/2.jpg`
- `img/logo.png`: `ios/HokejsSwift/Assets.xcassets/logo_eng.imageset/logo_eng.png`

Copy is based on that project's English store descriptions. App Store: https://apps.apple.com/app/id1533790213.

## Custom domain

GitHub Pages uses `hockey1984.eu` as its custom domain. Keep the root `CNAME` file committed.

DNS is managed at Zone using its existing nameservers. The apex uses GitHub Pages A records `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, and `185.199.111.153`. The `www` CNAME points to `coreteameu.github.io.`. GitHub manages the HTTPS certificate.
