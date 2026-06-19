# BLIT386

A palette-first WebGPU retro engine for TypeScript, inspired by [RetroBlit](https://badcastle.itch.io/retroblit). Draw with palette indices instead of RGBA pixels, animate with palette cycling and fades, and ship authentic VGA-era effects on modern GPUs – with an automatic Canvas 2D fallback when WebGPU is unavailable.

## Start a game in seconds

```bash
npm create blit386@latest my-game
```

Works with npm, pnpm, yarn, or bun. You get a ready-to-run Vite project, a commented starter game, and local docs.

![BLIT386 logo](https://github.com/blit386/blit386/raw/main/assets/logo.png)

## Projects

- **[blit386](https://github.com/blit386/blit386)** – the engine library ([npm](https://www.npmjs.com/package/blit386)).
- **[create-blit386](https://github.com/blit386/create-blit386)** – the `npm create blit386` scaffolder and [`@blit386/kit`](https://www.npmjs.com/package/@blit386/kit).
- **[blit386-demos](https://github.com/blit386/blit386-demos)** – interactive examples, hosted at [demos.blit386.dev](https://demos.blit386.dev).

## Why BLIT386?

- **True indexed rendering** - primitives and sprites write palette indices, not RGBA.
- **Palette effects built-in** - cycling, fade, flash, and swap run per frame, no per-sprite rewrites.
- **Retro palette presets** - VGA, CGA, C64, Game Boy, PICO-8, and NES.
- **Post-process effects** - a two-tier chain with bundled CRT presets.
- **Full input** - pointer, keyboard, and gamepad, plus a fixed-timestep loop and frame capture.

## Authors

- Václav Vančura ([@vancura](https://github.com/vancura))

## License

Licensed under ISC.
