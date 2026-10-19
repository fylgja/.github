<h1 align="center">
  <a href="https://fylgja.dev/">
    <img src="https://raw.githubusercontent.com/fylgja/.github/main/assets/readme-banner.webp" alt="Fylgja CSS: your modular CSS companion, take only what you need. Library, UI and docs at fylgja.dev" width="1280" height="320">
  </a>
</h1>

Fylgja CSS is a modular CSS library built around plain HTML. Pick exactly the parts you need, combine them with the tools you already use, and override anything without fighting specificity.

## What's inside

- **[Base](https://fylgja.dev/library/base/)**: classless defaults that make plain HTML look good, kept at zero specificity with `:where`.
- **[Tokens](https://fylgja.dev/library/tokens/)**: one design language as plain CSS variables, for colors, sizes, shadows, easing and more.
- **[Utilities](https://fylgja.dev/library/utilities/)**: a curated set of utilities you tune with a CSS variable instead of a new class.
- **[Components](https://fylgja.dev/library/components/)**: small, single class components such as card, badge, callout and toast.
- **[UI](https://fylgja.dev/ui/)**: components you copy, not dependencies you install. Plain, accessible HTML that works with any framework.

## Get started

```bash
npm install @fylgja/base
```

```css
@import "@fylgja/base";
```

No build step? Copy a file straight into your project with `npx fylgja@latest add theme`, or link it from a CDN. The [getting started guide](https://fylgja.dev/docs/) covers every option.

## Repositories

| Repository | What it is |
| --- | --- |
| [fylgja](https://github.com/fylgja/fylgja) | The monorepo with Base, Tokens, Utilities and the components |
| [site](https://github.com/fylgja/site) | The source of [fylgja.dev](https://fylgja.dev/), including Fylgja UI |
| [tailwindcss](https://github.com/fylgja/tailwindcss) | Tailwind CSS preset for the Fylgja design system |
| [snap-slider](https://github.com/fylgja/snap-slider) | A CSS powered slider, enhanced with JavaScript for accessibility |
| [css-attr-polyfill](https://github.com/fylgja/css-attr-polyfill) | Compiles CSS `attr()` v2 into static fallback rules |
| [stylelint-config](https://github.com/fylgja/stylelint-config) | The shareable stylelint config behind Fylgja's CSS rules |
| [php-props-builder](https://github.com/fylgja/php-props-builder) | Generate design tokens from PHP arrays or JSON |
| [alpinejs-dialog](https://github.com/fylgja/alpinejs-dialog) | Alpine.js helpers for the native HTML dialog |
| [examples](https://github.com/fylgja/examples) | Working examples with popular tools and frameworks |

## Follow along

Read the [blog](https://fylgja.dev/blog/) for releases and guides, or follow Fylgja on [Bluesky](https://bsky.app/profile/fylgja.dev), [Mastodon](https://fosstodon.org/@fylgja) and [DEV](https://dev.to/fylgja).

## Contributing

Issues, ideas and pull requests are welcome. Start with the [contributing guide](https://github.com/fylgja/.github/blob/main/.github/contributing.md), and if Fylgja is useful to you, a star on [fylgja/fylgja](https://github.com/fylgja/fylgja) helps others find it.
