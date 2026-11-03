<p align="center"><img src="docs/images/a-hero.png" alt="ArtCraft Free Plugin Store by NZO" width="100%"></p>

<p align="center">
<a href="../../releases/latest"><img src="docs/images/a-dl-win.png" alt="Download for Windows" width="250"></a>
<a href="../../releases/latest"><img src="docs/images/a-dl-mac.png" alt="Download for Mac" width="250"></a>
<a href="../../releases/latest"><img src="docs/images/a-dl-lin.png" alt="Download for Linux" width="250"></a>
</p>

<p align="center"><a href="README.fr.md">🇫🇷 Lire en français</a></p>

<p align="center"><img src="docs/images/a-tour.png" alt="A look inside the store" width="100%"></p>

<p align="center"><img src="docs/images/a-shelf.png" alt="The plugins" width="100%"></p>

<details>
<summary><b>📋 Every plugin, with what it does</b></summary>

| Plugin | Type | What it does | Inspired by |
|---|---|---|---|
| **3D Elements** | Panel | 3D text, models, materials, lighting, camera moves and object arrays on EffectCraft’s native GPU 3D renderer. Ready-made scenes included. | Element 3D |
| **AI Color Match** | Effect + panel | Matches the colors of a shot to a reference image. | AI Color Match |
| **Anonymizer** | Panel | Hides every face in a clip with a fake AI face, a blur or a pixelation, tracked and stackable. Needs the free local engine from [NZO-Anonymizer](https://github.com/Nozomagarion/NZO-Anonymizer/releases/latest) | Anonymizer |
| **Aperture Flare** | Effect | Customizable lens flares: 7 looks, star streaks, anamorphic streak, rainbow ring and aperture-shaped ghosts, every element adjustable. | Optical Flares |
| **ASCII Matrix FX** | Effect | ASCII rendering with block tearing. | RXXR |
| **Audio Keys** | Effect + panel | Audio spectrum and audio-driven keyframes. Apply to a solid using the panel. | Trapcode Sound Keys |
| **Auto Roto** | Panel | Subject cutouts using EffectCraft's Object Matte. Requires the MobileSAM model in EffectCraft settings. | — |
| **Cinema Suite** | Effect | Eleven cinema effects: film stock, warps, lens defocus, kaleidoscopes, halftone, motion blurs, sharpen and clarity, sketch and paint looks, relief and chrome, procedural textures, stained glass and mosaics. | Sapphire |
| **CorridorKey 2** | Effect + panel | Corridor Digital's CorridorKey 2.0 AI green-screen keyer, inside EffectCraft. Needs the free engine installer, Windows and an NVIDIA GPU. | CorridorKey 2.0 (Corridor Digital) |
| **Datamosh FX** | Effect + panel | Frame-by-frame datamosh with its control panel. | Motion Mosh |
| **Galactic Pixels** | Effect + panel | Temporal pixel effects, panel and block-map helper included. | Pixel Galactic |
| **GIF Shot** | Effect + panel | Export a composition or a batch through EffectCraft's render queue. | GifGun 2 |
| **Glass Studio & Liquid Glass** | Effect + panel | Both glass panels with their shared rendering engine. | AE Glass and Glasser |
| **Glowing Radiance** | Effect | Realistic HDR glow in linear light: hot core, long tail, dispersion, anamorphic stretch. | Deep Glow 2 |
| **Heat Sense** | Effect | Thermal palettes, grain and thermometers. | Heatmap |
| **Lumen Rays** | Effect | Volumetric light rays from a point: sun through trees, beams bursting from a title or logo. 9 light sources, 12 gradients, looping shimmer, 18 blend modes. | Trapcode Shine |
| **Mosh Pit** | Effect + panel | Datamosh algorithms and mosh markers. | Datamosh 2 |
| **Motion Isolate** | Effect + panel | Isolates motion using a temporal rig. | Motion Extractor |
| **N-Glitch** | Effect | Digital compression glitches and distortion. | Jlitch |
| **Natural Typer** | Effect + panel | Natural text typing with adjustable timing. | WriteTyper |
| **Nebula Gradients** | Effect | Animated nebula gradients and colour textures. | Cosmic |
| **Node Forge** | Effect + panel | 27 looks in one click each, plus a node editor. | GPUDog Deep |
| **Pixel Sort Pro** | Effect | Pixel sorting with directional controls. | Pixel Sorter |
| **Plasma Neon** | Effect | Energy beams, neon tubes and lasers: line, circle, text outline or whole layer, 10 looks, animated distortion and flicker. | Saber |
| **Shape Morph** | Panel | One-click shape and text morphing: six feels, sequences, plain path keyframes. | Morph Studio |
| **Signal Pack** | Effect | Four glitch and retro effects: Signal Glitch, VHS Tape, CRT Screen and Glitch Transition. | Universe |
| **Trace FUI** | Effect + panel | Futuristic tracing effect with its temporal rig. | Tracery 2 |
| **Track Forge** | Panel | Point, planar and 3D camera tracking with a 2026 AI tracker, plus a one-click export to Blender. Needs the free local engine from [NZO-TrackForge](https://github.com/Nozomagarion/NZO-TrackForge/releases/latest) | Mocha Pro and SynthEyes |
| **VoxelSort FX** | Effect | Volumetric pixel sorting, presets included. | Voxel Sorter |

</details>

## ✏️ Good to know

<details>
<summary><b>🪟 Windows says "Windows protected your PC"</b></summary>

Unzip **NZO-Store-Windows.zip**, open **NZO Store.exe**, then click **More info** and **Run anyway**. The app is not signed with a paid Microsoft certificate. Windows only asks once.
</details>

<details>
<summary><b>🍎 Mac says the app can’t be opened</b></summary>

Take **Apple Silicon** for M1 to M4 Macs, **Intel** for older ones (Apple menu ▸ About This Mac). Drag the app into Applications and open it once. Then go to **System Settings ▸ Privacy & Security**, scroll down and click **Open Anyway**. You only do this once: the app is not signed with a paid Apple account.
</details>

<details>
<summary><b>🐧 Linux</b></summary>

Unzip **NZO-Store-Linux.zip** and run `./install.sh` to add it to your apps menu. The store opens in your browser.
</details>

<details>
<summary><b>🧩 Which Craft apps?</b></summary>

The store has a tab for each Craft app: **EffectCraft, FilmCraft, GridCraft, LightCraft, PdfCraft and PhotoCraft**. Today the 29 plugins are for EffectCraft. The other apps are open: as soon as a plugin is published for one of them, it shows up in its tab, without reinstalling anything.

The store never modifies the apps themselves. It only copies plugin files into each app’s own plugin folders, and **Remove** deletes exactly what it installed.
</details>

<details>
<summary><b>📤 Share your own plugin</b></summary>

Press **Submit plugin** in the app, pick the Craft app it is for, and send a `.zip` (20 MB max) with only `.wasm`, `.jsx`, `.ecpreset`, `.json`, `.png`, `.md` or `.txt` files. Add an `icon.png` (square, 300 KB max) and, if you like, a `store.json` and a `gallery/` folder for a nicer page. Your name is credited as the creator, with a **Community** badge. Every submission is checked, and a person approves it before it goes live.
</details>

<details>
<summary><b>🔒 Is it safe?</b></summary>

- Every download is checked against its SHA-256 fingerprint. If it doesn’t match, nothing is installed.
- The app only copies files. It never runs a plugin and never changes the Craft apps.
- Community plugins go through quarantine: an automatic scan, then a person reads any script before it is published.
- App updates come from this repository’s Releases and are checked the same way.
</details>

<details>
<summary><b>❓ Is it free? Is it official?</b></summary>

Free, yes: the app and every plugin (MIT licence). Official, no: it is an unofficial community project, not affiliated with ArtCraft. The plugins are original NZO code inspired by well-known plugins, whose names belong to their owners. CorridorKey 2 is built on CorridorKey 2.0 by Corridor Digital, under its licence.
</details>

<br>

<p align="center"><img src="docs/images/a-footer.png" alt="ArtCraft Free Plugin Store by NZO" width="100%"></p>

