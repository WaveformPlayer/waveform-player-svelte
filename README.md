> [!IMPORTANT]
> **Replaced by [`@arraypress/waveform-svelte`](https://www.npmjs.com/package/@arraypress/waveform-svelte) 2.0.** Import from `@arraypress/waveform-svelte/player` instead — one package per framework, with a sub-path per component ([repo](https://github.com/WaveformPlayer/svelte), [migration guide](https://docs.waveformplayer.com/getting-started/migrating-from-1x/)).
> This repository is archived and the npm package is deprecated; its 1.x releases keep working.

<div align="center">

# WaveformPlayer for Svelte

**Svelte 5 component wrapper for [`@arraypress/waveform-player`](https://github.com/WaveformPlayer/waveform-player).**
Typed props for every option, callback props, an exported imperative API, and SSR-safe mounting.

[![npm version](https://img.shields.io/npm/v/@arraypress/waveform-player-svelte?style=flat-square&labelColor=09090b&color=3f3f46)](https://www.npmjs.com/package/@arraypress/waveform-player-svelte)
[![license](https://img.shields.io/npm/l/@arraypress/waveform-player-svelte?style=flat-square&labelColor=09090b&color=3f3f46)](https://github.com/WaveformPlayer/waveform-player-svelte/blob/main/LICENSE)

**[Documentation](https://docs.waveformplayer.com/)** &middot; [npm](https://www.npmjs.com/package/@arraypress/waveform-player-svelte)

</div>

---

## Install

```bash
npm install @arraypress/waveform-player-svelte @arraypress/waveform-player svelte
```

> **Requires `@arraypress/waveform-player` 1.27.0 or newer.** The component
> loads the core library's `/no-autoinit` entry point, so that it never scans
> the page for markup it doesn't own — that subpath was added in 1.27.0. If
> you're upgrading this package on its own, bump the core alongside it.

```svelte
<script lang="ts">
  import { WaveformPlayer } from '@arraypress/waveform-player-svelte';
  import '@arraypress/waveform-player/dist/waveform-player.css';
</script>

<WaveformPlayer url="/track.mp3" title="My Song" artist="The Artist" />
```

## Documentation

Full props, the imperative API, styling, and framework guides live on the docs site.

### -> [docs.waveformplayer.com](https://docs.waveformplayer.com/)

[Svelte guide](https://docs.waveformplayer.com/frameworks/svelte/) — install, props, the imperative API, and SSR notes. All four Svelte wrappers (player / bar / playlist) are on that page.

## License

MIT © [ArrayPress](https://github.com/arraypress)
