# threejs-waterflow-animation

A waterfall-of-light animation built with **Three.js** and plain HTML.

## Effect overview

| Layer | Description |
|-------|-------------|
| **Core** | Bright white-violet column – tightly concentrated at the centre axis |
| **Inner ring** | Medium violet particles forming the body of the stream |
| **Outer ring** | Deep purple halo that fans out toward the bottom |
| **Mist / smoke** | Large, near-transparent dark-purple particles wrapping the outer edge |

All layers use **Additive blending** so overlapping particles create a natural bloom glow.  
The stream is **narrow at the top** and **fans out at the bottom**, matching the physics of a real waterfall.  
A pulsing purple rim-light adds a subtle scene-level glow.

## Usage

Open `index.html` directly in any modern browser – no build step or server required.

```
open index.html   # macOS
xdg-open index.html   # Linux
start index.html  # Windows
```

Three.js r128 is loaded from the cdnjs CDN, so an internet connection is needed on first load.
