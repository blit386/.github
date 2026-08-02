# BLIT386

A palette-first WebGPU retro engine for TypeScript, inspired by [RetroBlit](https://www.badcastle.com/retroblit.html) by
Martin Cietwierkowski ([@daafu](https://github.com/daafu)). Draw with palette indices instead of RGBA pixels, animate
with palette cycling and fades, and ship authentic VGA-era effects on modern GPUs – with an automatic Canvas 2D fallback
when WebGPU is unavailable.

Read the documentation at [blit386.dev](https://blit386.dev).

## Start a game in seconds

```bash
npm create blit386@latest my-game
```

Works with npm, pnpm, yarn, or bun. You get a ready-to-run Vite project, a commented starter game, and local docs.

![BLIT386 logo](https://github.com/blit386/blit386/raw/main/assets/logo.png)

## Projects

[blit386/blit386](https://github.com/blit386/blit386) is a single monorepo holding everything below. The engine
anchors it; the other packages release in lockstep with it.

- [packages/blit386](https://github.com/blit386/blit386/tree/main/packages/blit386) – the engine library
  ([npm](https://www.npmjs.com/package/blit386)).
- [packages/create-blit386](https://github.com/blit386/blit386/tree/main/packages/create-blit386) and
  [packages/kit](https://github.com/blit386/blit386/tree/main/packages/kit) – the `npm create blit386` scaffolder and
  [`@blit386/kit`](https://www.npmjs.com/package/@blit386/kit).
- [packages/demos](https://github.com/blit386/blit386/tree/main/packages/demos) – interactive examples, hosted at
  [demos.blit386.dev](https://demos.blit386.dev).
- [packages/website](https://github.com/blit386/blit386/tree/main/packages/website) – source for
  [blit386.dev](https://blit386.dev).
- [awesome-blit386](https://github.com/blit386/awesome-blit386) – a curated list of BLIT386 resources and community
  games.

## Why BLIT386?

- True indexed rendering – primitives and sprites write palette indices, not RGBA.
- Palette effects built-in – cycling, fade, flash, and swap run per frame, no per-sprite rewrites.
- Retro palette presets – VGA, CGA, C64, Game Boy, PICO-8, and NES.
- Post-process effects – a two-tier chain with bundled CRT presets.
- Full input – pointer, keyboard, and gamepad, plus a fixed-timestep loop and frame capture.

## Community

- [Discord](https://discord.gg/tC2wGt88Uj)
- [GitHub Discussions](https://github.com/blit386/blit386/discussions)
- [X](https://x.com/blit386)
- [Bluesky](https://bsky.app/profile/blit386.bsky.social)
- [Mastodon](https://mastodon.gamedev.place/@blit386)

## Authors

- Václav Vančura ([@vancura](https://github.com/vancura))

## License

Licensed under ISC.
