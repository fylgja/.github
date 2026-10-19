<div align="center">
<h1>
  <a href="https://fylgja.dev/">
    <img src="https://raw.githubusercontent.com/fylgja/.github/main/assets/logo.svg" alt="Fylgja" width="300" height="130">
  </a>
</h1>
</div>

<h3 align="center">Fylgja .github</h3>

The organization wide files for every repository in [Fylgja](https://github.com/fylgja), plus the shared brand assets they use.

## What's in here

| Path | What it does |
| --- | --- |
| [`profile/README.md`](profile/README.md) | The profile shown on [github.com/fylgja](https://github.com/fylgja) |
| [`.github/contributing.md`](.github/contributing.md) | The default contributing guide for repositories without their own |
| [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | The default code of conduct for repositories without their own |
| [`assets/logo.svg`](assets/logo.svg) | The Fylgja wordmark, used at the top of each README |
| [`assets/readme-banner.webp`](assets/readme-banner.webp) | The banner on the organization profile |
| [`assets/badge/`](assets/badge) | A [Shields.io endpoint](https://shields.io/badges/endpoint-badge) for the Fylgja badge |

## Using the shared assets

Link to the raw files so every README picks up changes from one place.

```html
<img src="https://raw.githubusercontent.com/fylgja/.github/main/assets/logo.svg" alt="Fylgja" width="300" height="130">
```

```md
[![Fylgja](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ffylgja%2F.github%2Frefs%2Fheads%2Fmain%2Fassets%2Fbadge%2Fv1.0.0.json)](https://fylgja.dev/)
```

The banner sources and render script live in the [site repository](https://github.com/fylgja/site), under `.agents/skills/create-og-banner`.
