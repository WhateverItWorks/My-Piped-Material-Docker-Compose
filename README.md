# Piped-Material

[![GitHub Repo stars](https://img.shields.io/github/stars/mmjee/Piped-redesign?style=social)](https://github.com/mmjee/Piped-redesign/stargazers)
[![GitHub last commit](https://img.shields.io/github/last-commit/mmjee/Piped-redesign)](https://github.com/mmjee/Piped-redesign/commits)
[![Weblate Translation Status](https://hosted.weblate.org/widgets/piped-material/-/i18n/svg-badge.svg)](https://hosted.weblate.org/projects/piped-material/i18n/#information)

Piped-Material is a fork of [Piped](https://github.com/TeamPiped/piped), an alternative client to YouTube. I have tried to improve the performance, the design and efficiency.

There are a few things that PM does better, like watch history tracking, and compares favorably to Piped's features.

As a byproduct, the code is also much cleaner, dysfunctional patterns and paradigms have been replaced with clean, beautiful code :).

There's an branch implementing preferences & watch history syncing, with PBKDF2-based or Web3 wallet-based key generation using [EDS](https://git.maharshi.ninja/root/libeds) at the `feature-eds_2` branch. This is deployed [at eds-v2.piped.১.net](https://eds-v2.piped.১.net).

There are two deprecated deployments, that use a older version of EDS that is no longer supported and does not receive updates. It's still maintained to for users who still have not migrated, but will be deleted soon. The newer version is incompatible with the older version and generates entirely different keys.

## Links

| URL                           | Environment | Special Notes  | Default Instance |
|-------------------------------|-------------|----------------|------------------|
| https://piped-material.১.net  | Production  |                | Kavin            |
| https://piped-material.ftp.sh | Production  |                | Kavin            |
| https://eds-v2.piped.১.net    | Production  | EDS-V2         | Kavin            |
| https://piped-staging.ftp.sh  | Staging     |                | Kavin            |
| https://ui.piped.১.net        | Staging     | IPv6-only      | mmjee            |
| https://ng.piped.১.net        | Deprecated  | IPv6-only, EDS | mmjee            |
| https://ngp.piped.১.net       | Deprecated  | EDS-Password   | Kavin            |

Production instances are updated infrequently, and do not include features that are introduced recently without extensive testing.

Piped-Material's Production instance is also available via IPFS at IPNS key `k51qzi5uqu5dl0a18rats73hcc6d5dtvtz9pjbpgzj6hl66b9za5i5wn0yzgjv`.
For example, it's available [via dweb.link](https://k51qzi5uqu5dl0a18rats73hcc6d5dtvtz9pjbpgzj6hl66b9za5i5wn0yzgjv.ipns.dweb.link) and [via cf-ipfs.com](https://k51qzi5uqu5dl0a18rats73hcc6d5dtvtz9pjbpgzj6hl66b9za5i5wn0yzgjv.ipns.cf-ipfs.com).

## Deploy with Docker (Easy & Recommended)
```
docker-compose up -d --build
```

## Help

Join the Libera Chat IRC Channel: ircs://irc.libera.chat:6697/#piped-material

Join the Matrix Chat Channel: #piped-material:libera.chat

## How to contribute

One of the easiest and most important ways to contribute is to translate and localize it to your language and/or region.

You can use Weblate for this, or you can just send normal PRs or patches.

Weblate URL: [https://hosted.weblate.org/projects/piped-material/i18n](https://hosted.weblate.org/projects/piped-material/i18n).

## Backlog

- [ ] Playing videos continuously in a playlist

## Features:

- [x] No Ads
- [x] No Tracking
- [x] Infinite Scrolling
- [x] 4K support
- [x] No connections to Google's servers
- [x] Comments
- [x] Playlist support
- [x] Captions support
- [x] Search Suggestions
- [x] Livestreams support with a quality selector
- [x] Support for IOS
- [x] Preferences saved locally
- [x] Multi-region loadbalancing
- [x] Performant by design, designed to handle 1000s of users concurrently
- [x] PWA support
- [x] Improving UI
- [x] Login
- [x] Feeds
- [x] Integration with SponsorBlock
- [x] Integration with LBRY
- [x] Playing just audio

## WIP

- [ ] 8K support

## Documentation

The original parent repository documentation can be found at https://piped-docs.kavin.rocks (accessible via IPNS as well).

## Screenshots

![Screenshot 1](https://bafybeie4ulcmyw6fazbk7wwpqhe4l73mvvm7fayuv7g47ywqavotkjh2jy.ipfs.dweb.link/?filename=img1.webp)
![Screenshot 2](https://bafybeieg5li3ldla6i4balyomrm7ccrn6wlvsqit4chig6phmuitqqhhpi.ipfs.dweb.link/?filename=img2.webp)

To donate and for support, [see TeamPiped/piped](https://github.com/TeamPiped/piped)
