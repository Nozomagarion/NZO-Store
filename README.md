<p align="center"><img src="docs/images/banner.png" alt="NZO Store" width="100%"></p>

<h3 align="center">Free plugins for EffectCraft, one click away.</h3>

<p align="center">
Browse a beautiful catalogue, press <b>Install</b>, restart EffectCraft. That's it.<br>
<sub>Windows · Mac · Linux · no account · the app updates itself</sub>
</p>

<p align="center">
<a href="../../releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/Nozomagarion/NZO-Store?style=for-the-badge&label=Download&color=111111"></a>
<img alt="Plugins" src="https://img.shields.io/badge/plugins-29-0a7563?style=for-the-badge">
<img alt="Platforms" src="https://img.shields.io/badge/Windows_·_Mac_·_Linux-1659c4?style=for-the-badge">
<img alt="Licence" src="https://img.shields.io/badge/licence-MIT-7a4be0?style=for-the-badge">
</p>

<p align="center">
<a href="../../releases/latest"><b>⬇ Download the latest version</b></a> · <a href="README.fr.md">🇫🇷 Lire en français</a>
</p>

<p align="center"><img src="docs/media/catalogue.gif" alt="The NZO Store catalogue, dark and light" width="880"></p>
<p align="center"><sub>The catalogue. Dark or light, the store follows your system.</sub></p>

---

## ✨ What is NZO Store?

NZO Store is a small desktop app that gives **EffectCraft** its own plugin store, a bit like the add-on store in Blender. No hidden folders, no zip files to unpack by hand: open the store, pick a plugin, press **Install**.

| | |
|---|---|
| 🆓 **Free** | Every plugin in the store is free (MIT licence). The app too. |
| 🛡️ **Safe** | Every download is checked against its SHA-256 fingerprint before anything is installed. |
| 🧘 **Simple** | Windows, Mac and Linux. No account, no sign-up. |
| 🤝 **Respectful** | It never modifies EffectCraft itself. It only copies plugin files into EffectCraft's own plugin folders. |
| 🔄 **Self-updating** | Since 1.0.4, a banner tells you when a new version is out. One click and the app updates itself. |

---

## ⚡ Install a plugin in 10 seconds

<p align="center"><img src="docs/media/install.gif" alt="Search a plugin and install it" width="880"></p>

1. **Search** or scroll to the plugin you want.
2. Press **Install**. The store downloads it, checks its fingerprint and copies the files.
3. **Restart EffectCraft.** Effects appear in the **Effect** menu, panels in **Window ▸ NZO**.

> Already installed some plugins by hand? The store recognises them when the files are the same, and offers to replace them if yours are an older version.

---

## 🎬 A tour of the app

### Every plugin has its own page

What it does, how to use it step by step, previews, version and fingerprint. Each plugin brings its own colours.

<p align="center"><img src="docs/media/plugin-page.gif" alt="Opening a plugin page" width="880"></p>

### Filters, search and a table view

Filter by **Installed**, **Updates** or **Not installed**, sort by name or by date, or switch to the compact **Table** view.

<p align="center"><img src="docs/media/table.gif" alt="Filters and table view" width="880"></p>

### Updates, for plugins and for the app

When a plugin has a new version, an **Update all** button appears. When the app itself has a new version, a banner shows up: **Update now** downloads it, checks its fingerprint, replaces the app and restarts it. You never need to download the app by hand again.

<p align="center"><img src="docs/media/update.gif" alt="Update all plugins and update the app" width="880"></p>

### English or French

One click on **EN / FR** switches the whole store, plugin pages included.

<p align="center"><img src="docs/media/language.gif" alt="Switching the store to French" width="880"></p>

---

## ⬇️ Download and install the app

| Your computer | File to download |
|---|---|
| 🪟 Windows | **NZO-Store-Windows.zip** |
| 🍎 Mac with an Apple chip (M1, M2, M3, M4…) | **NZO-Store-Mac-Apple-Silicon.zip** |
| 🍎 Older Mac with an Intel chip | **NZO-Store-Mac-Intel.zip** |
| 🐧 Linux (64-bit, x86) | **NZO-Store-Linux.zip** |

All files are on the [**Releases page**](../../releases/latest), under *Assets*.

> Not sure which Mac you have? Apple menu ▸ **About This Mac**. *Apple M…* means Apple Silicon, *Intel* means Intel.

<details>
<summary><b>🪟 Windows, step by step</b></summary>

1. Download **NZO-Store-Windows.zip** and unzip it.
2. Open **NZO Store.exe**.
3. If Windows shows *"Windows protected your PC"*: click **More info**, then **Run anyway**.

> Why this message? The app is new and not signed with a paid Microsoft certificate. It is safe, and Windows only asks once.
</details>

<details>
<summary><b>🍎 Mac, step by step</b></summary>

1. Download the right zip (see the table), open the **.dmg** and drag **NZO Store** into **Applications**.
2. Open it. macOS will probably say it **can't be opened** or comes from an **unidentified developer**. Click **OK**.
3. Open **System Settings ▸ Privacy & Security**, scroll all the way down and click **Open Anyway** next to *NZO Store*. Confirm with your password. You only do this once.

> ⚠️ The app isn't signed with a paid Apple Developer account, so macOS blocks it the first time. It's not a virus, we just haven't paid Apple. On older versions of macOS, right-click the app and choose **Open** instead.
</details>

<details>
<summary><b>🐧 Linux, step by step</b></summary>

1. Download **NZO-Store-Linux.zip** and unzip it.
2. Run `./install.sh` from that folder to add **NZO Store** to your applications menu (or just open the **NZO Store** file directly).
3. The store opens in your web browser.
</details>

The same steps are always available inside the app, under **Install guide**.

---

## 🧩 The plugins

29 plugins today, and the list grows without reinstalling anything: the store fetches new ones on its own.

Every plugin is **original NZO code**, inspired by a well-known plugin so you know what to expect. The store is not affiliated with any of them.

<details>
<summary><b>See the full list</b></summary>

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

<p align="center"><img src="docs/images/montage.png" alt="Some of the plugins" width="880"></p>

---

## 📤 Submit your own plugin

Made something for EffectCraft? Send it in with the **Submit plugin** button in the app. Your name is credited as the creator on the plugin page.

<p align="center"><img src="docs/media/submit.gif" alt="The Submit plugin form and the install guide" width="880"></p>

1. Put your files in a `.zip` (20 MB at most) containing only `.wasm`, `.jsx`, `.ecpreset`, `.json`, `.png`, `.md` or `.txt` files.
2. Add an `icon.png` (square, up to 300 KB) at the root to give your plugin its picture.
3. Optional but nice: add a `store.json` to give your plugin its own colours and a full page, and a `gallery/` folder with up to six PNG screenshots.

<details>
<summary><b>Example of <code>store.json</code></b></summary>

```json
{
  "palette": ["#ff4d2e", "#ffb02e", "#fff3a1"],
  "tagline": "See the world in thermal vision.",
  "about": ["One or two short paragraphs about what it does."],
  "features": [{"g": "flame", "t": "Thermal palettes", "d": "From white hot to iron-bow."}],
  "steps": [{"t": "Apply the effect", "d": "Effect ▸ NZO ▸ Heat Sense."}]
}
```

Add `_fr` versions of the text fields (`tagline_fr`, `about_fr`…) for a French page. Feature icons (`g`): `wave`, `grid`, `flame`, `sparkles`, `layers`, `sliders`, `film`, `type`, `scissors`, `cube`, `bolt`, `eye`, `palette`, `download`, `target`.
</details>

Nothing is published automatically. Every submission goes through the checks below and a person approves it.

<p align="center"><img src="docs/images/pipe.png" alt="From submission to publication" width="880"></p>

---

## 🔒 Security

- **SHA-256 on every download.** The app compares the fingerprint of each file with the one in the catalogue and refuses to install if they differ.
- **The app only copies files** into EffectCraft's plugin folders. It never runs a plugin, and it never changes EffectCraft.
- **Safe-by-design paths.** Files with tricky paths (`../`), links, wrong types or fake `.wasm` are refused. Archives that are too big are refused.
- **Community plugins go through quarantine.** An automatic scan refuses obviously dangerous code, such as network access, running commands or hidden code. Anything with a `.jsx` script is always read by a person before it is published.
- **The app updates itself safely too.** The new version is downloaded from this repository's Releases and its SHA-256 is checked before the app is replaced.
- **Upload limits:** 5 per hour per person, 20 MB per zip.

Found a problem? Please open an issue on this repository.

---

## 📁 Where do the plugins go?

You never have to touch these folders, but here they are:

| System | Folder |
|---|---|
| Windows | `%APPDATA%\EffectCraft` |
| macOS | `~/Library/Application Support/EffectCraft` |
| Linux | `~/.config/effectcraft` |

Effects (`.wasm`) go in `Plug-ins`, panels (`.jsx`) go in `Scripts/ScriptUI Panels`, and presets (`.ecpreset`) go in `Documents/EffectCraft/Presets`. In EffectCraft, **effects** appear in the **Effect** menu (look for the **NZO** entries) and **panels** in **Window ▸ NZO**.

---

## ❓ FAQ

<details>
<summary><b>Is it really free?</b></summary>
Yes. The app and all plugins in the store are free.
</details>

<details>
<summary><b>Is it official?</b></summary>
No. NZO Store is an unofficial, community project. It is not affiliated with EffectCraft or ArtCraft.
</details>

<details>
<summary><b>Will it break my EffectCraft?</b></summary>
No. It only adds files to the same plugin folders you would use by hand, and <b>Remove</b> deletes exactly what the store installed.
</details>

<details>
<summary><b>The store says "built-in catalogue" or offline.</b></summary>
The built-in plugins can still be installed without a connection. The server is only needed for newer versions and community plugins.
</details>

<details>
<summary><b>Mac says the app is damaged or can't be opened.</b></summary>
Follow the <b>Open Anyway</b> steps above. It happens because the app is not signed with a paid Apple account.
</details>

<details>
<summary><b>I already installed some plugins myself.</b></summary>
The store recognises them automatically when the files are the same.
</details>

<details>
<summary><b>Which EffectCraft version do I need?</b></summary>
Plugins are built for EffectCraft's plugin system (WASM effects and ScriptUI panels). If a plugin page lists extra requirements, such as a model to enable in EffectCraft's settings, follow them.
</details>

---

## 💛 Credits and licence

Plugins in the store are released under the MIT licence (each zip contains its `LICENSE.txt`).

NZO Store is an unofficial community project and is not affiliated with EffectCraft or ArtCraft. The plugins are original NZO code, inspired by well-known plugins whose names belong to their owners. CorridorKey 2 is built on CorridorKey 2.0 by Corridor Digital, under its licence. Fonts: Inter, Archivo and Geist Mono (SIL Open Font License).

<p align="center"><sub>Made with care by <b>Nozomagarion</b>.</sub></p>
