# carsmash

The recovered ifreelgood.com interactive pixel-car site. Press the car to advance through 14 original animation frames; reset rebuilds it.

## Run locally

```sh
python3 -m http.server 8000 --directory dist
```

Open http://localhost:8000. No dependencies or build step are required.

## Cloudflare Pages

- Production branch: `main`
- Framework preset: None
- Build command: leave empty
- Build output directory: `dist`

The deployable site is in `dist/`, including all images. Artwork provenance is in `ASSET-SOURCES.md`.

## Recovery

Recovered byte-for-byte from saved site version 3, source commit `798805a4f7dbcc188faac001e36a8cea4d5fb21f`. All 18 original tracked files are preserved, including the existing Sites configuration. Image decoding and JavaScript syntax checks passed; every uploaded source file's Git blob hash matched the recovered source.
