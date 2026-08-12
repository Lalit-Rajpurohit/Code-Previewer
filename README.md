<div align="center">

<img src="assets/banner.png" width="100%" alt="Code Previewer — code view, folder view, compare files, markdown preview">

<br><br>

**Open any local source file in your browser — rendered like VS Code.<br>No server. No upload. No internet. Just `file://` done right.**

<br>

![Manifest V3](https://img.shields.io/badge/Manifest-V3-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-strict-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Offline](https://img.shields.io/badge/100%25-OFFLINE-4ade80?style=for-the-badge)

![Version](https://img.shields.io/badge/v1.13.1-8b5cf6?style=flat-square&label=version)
![Languages](https://img.shields.io/badge/25%2B-languages-0ea5e9?style=flat-square)
![Privacy](https://img.shields.io/badge/telemetry-none-22c55e?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-64748b?style=flat-square)

<br>

[![Available on the Chrome Web Store](assets/badge-chrome.svg)](https://chromewebstore.google.com/detail/code-previewer/jpmbjliabobhdapdnhpdhiehdfleddjg)
&nbsp;&nbsp;&nbsp;
[![Available on Microsoft Edge Add-ons](assets/badge-edge.svg)](https://microsoftedge.microsoft.com/addons/detail/code-previewer/kjelmbmjipkbncoclckieombhjgjpeei)

**🌐 [lalit-rajpurohit.github.io/Code-Previewer](https://lalit-rajpurohit.github.io/Code-Previewer/)**

<br>

<img src="assets/demo.gif" width="860" alt="Code Previewer demo — folder view, themes, markdown preview, mermaid diagrams and file compare">

</div>

---

## 📸 Screenshots

<div align="center">

| Code view · Python | Folder view |
| :---: | :---: |
| ![](assets/screenshot-1.png) | ![](assets/screenshot-2.png) |

| Compare files | Markdown + Mermaid | Mermaid file |
| :---: | :---: | :---: |
| ![](assets/screenshot-3.png) | ![](assets/screenshot-4.png) | ![](assets/screenshot-5.png) |

</div>

## ⚡ `$ code-previewer --features`

```console
$ code-previewer --features

  ✓ syntax highlighting ....... 25+ languages, VS Code-grade colors
  ✓ folder view ............... browse folders as a grid — badges, filter,
                                sort, breadcrumbs, keyboard navigation
  ✓ compare mode .............. side-by-side diff of any two files
  ✓ markdown preview .......... split / preview-only / source-only,
                                with highlighted code blocks
  ✓ mermaid diagrams .......... .mmd / .mermaid files and ```mermaid blocks
  ✓ themes .................... ☀ Light · 🌙 One Dark · ☁ GitHub Light · 🧛 Dracula
  ✓ search .................... Ctrl+F panel — regex, match case, by word
  ✓ editor extras ............. line numbers · code folding · word wrap
  ✓ file actions .............. copy · download · reload · fullscreen · back
  ✓ privacy ................... zero network calls — files never leave
                                your machine

$ _
```

## 🗂 Language support

```text
╭──────────────┬──────────────┬──────────────┬──────────────┬──────────────╮
│  Python      │  JavaScript  │  TypeScript  │  JSON        │  YAML        │
│  HTML        │  CSS         │  Java        │  Go          │  Rust        │
│  C / C++     │  SQL         │  XML / SVG   │  Markdown    │  Shell       │
│  Dockerfile  │  Mermaid     │  Terraform   │  TOML / INI  │  + more...   │
╰──────────────┴──────────────┴──────────────┴──────────────┴──────────────╯
```

> Unknown-but-texty extensions fall back to a clean plain-text view — so *any* code file opens.

## 📁 Folder view

Open a **directory** instead of a file — `file:///C:/projects/` — and the bare Chrome listing
becomes a proper file browser:

- Grid of files and sub-folders with **language badges** and type icons
- **Filter** box, **A→Z / Z→A** sort, clickable **breadcrumbs**
- **Keyboard navigation** — type to filter, arrows to move, <kbd>Enter</kbd> to open,
  <kbd>Backspace</kbd> to go up
- Optional **"Enable folder access"** (standard File System Access API, one click):
  preview files in a side pane and **compare any two** with checkboxes

## 🧜 Mermaid diagrams

- `.mmd` and `.mermaid` files render as diagrams, with the source alongside
- ` ```mermaid ` blocks inside Markdown render inline in the preview
- Diagrams follow the active theme — light and dark both look right
- A syntax error shows the message in place instead of breaking the page

## 🎨 Themes

| | Theme | Vibe |
| :---: | --- | --- |
| ☀ | **Light** | clean default, easy on projectors |
| 🌙 | **One Dark** | the Atom classic |
| ☁ | **GitHub Light** | familiar PR-review feel |
| 🧛 | **Dracula** | because obviously |

One click cycles through all four — your pick is remembered across sessions.

## 📦 Install

```console
$ how-to-install

  [1] Chrome  →  https://chromewebstore.google.com/detail/code-previewer/jpmbjliabobhdapdnhpdhiehdfleddjg
      Edge    →  https://microsoftedge.microsoft.com/addons/detail/code-previewer/kjelmbmjipkbncoclckieombhjgjpeei

  [2] Extension Details → ✓ "Allow access to file URLs"     (one-time, required)

  [3] Open any local file or folder:

      file:///C:/projects/main.py        ← boom. syntax highlighted.
      file:///C:/projects/               ← folder view
```

## ⌨️ Shortcuts

| Keys | Action |
| --- | --- |
| <kbd>Ctrl</kbd> + <kbd>F</kbd> | Search within file |
| <kbd>Enter</kbd> / <kbd>Shift</kbd> + <kbd>Enter</kbd> | Next / previous match |
| <kbd>Alt</kbd> + <kbd>Z</kbd> | Toggle word wrap — in compare mode, only the pane your cursor is in |
| <kbd>Esc</kbd> | Close search panel |
| <kbd>▸</kbd> gutter click | Fold / unfold a code block |
| *In folder view* | type to filter · <kbd>←↑↓→</kbd> move · <kbd>Enter</kbd> open · <kbd>Backspace</kbd> up |

## 🔒 Privacy

```diff
+ everything runs locally in your browser
+ the only stored setting is your theme preference
- no analytics
- no telemetry
- no network requests
- no accounts, ever
```

## 🧭 Roadmap

- [x] Syntax highlighting — 25+ languages
- [x] 4 themes with persistence
- [x] Side-by-side compare mode with per-pane word wrap
- [x] Markdown preview — split / preview-only / source-only
- [x] Search, folding, copy, download, reload, fullscreen
- [x] **Published on the Chrome Web Store**
- [x] **Published on Microsoft Edge Add-ons**
- [x] Folder view with grid, filter, sort and keyboard navigation
- [x] Mermaid diagram rendering
- [x] Syntax-highlighted code blocks in the markdown preview
- [ ] Minimap
- [ ] More themes

## ⚠️ Known limitations

- `.ts` files may open as a media player — Chrome maps `.ts` to `video/mp2t` before any
  extension can act. Rename to `.mts` / `.tsx` if it bites you.
- Terraform (`.tf`) renders as plain text — no CodeMirror grammar exists for HCL.
- Files over 10 MB fall back to the browser's native view.

<br>

---

<div align="center">

**If this is useful, drop a ⭐ — it genuinely helps.**

<sub>`Rendered by Code Previewer` · MIT License · <a href="https://lalit-rajpurohit.github.io/Code-Previewer/">live site</a></sub>

</div>
