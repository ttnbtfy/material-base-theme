# 🌈 Material Base Theme

[![Version](https://img.shields.io/visual-studio-marketplace/v/1dem2nhay.material-base-theme?label=Marketplace&color=80CBC4)](https://marketplace.visualstudio.com/items?itemName=1dem2nhay.material-base-theme)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/1dem2nhay.material-base-theme?color=82AAFF)](https://marketplace.visualstudio.com/items?itemName=1dem2nhay.material-base-theme)
[![License: MIT](https://img.shields.io/badge/license-MIT-C792EA)](https://github.com/ttnbtfy/material-base-theme/blob/master/LICENSE)

A calm, Material-inspired dark theme with a blue-grey palette.
Every part of the window — editor, sidebar, panels, widgets and status bar — shares the same tones, and the status bar no longer jumps to purple or orange when no folder is open or while debugging.

Works in **VS Code**, **VSCodium** and other VS Code–compatible editors.

![Material Base Theme](https://raw.githubusercontent.com/ttnbtfy/material-base-theme/master/images/ui.png)

---

## 🚀 Installation

**VS Code**
1. Open the Extensions view (`Ctrl+Shift+X`).
2. Search for `Material Base Theme` and click **Install**.
3. `Ctrl+Shift+P` → **Preferences: Color Theme** → **Material Base Theme**.

Or from a terminal:

```sh
code --install-extension 1dem2nhay.material-base-theme
```

**VSCodium and other editors**
1. Download the latest `.vsix` from [GitHub Releases](https://github.com/ttnbtfy/material-base-theme/releases/latest).
2. Extensions view → `...` → **Install from VSIX...** and pick the downloaded file.
3. Select **Material Base Theme** as your color theme.

---

## 🎨 Palette

| Role | Color |
|---|---|
| Editor background | `#263238` |
| Sidebar / title bar | `#171e22` |
| Status bar | `#13191c` |
| Widgets (hover, suggest, menus) | `#1e272c` |
| Accent | `#80CBC4` |
| Keywords | `#C792EA` |
| Functions | `#82AAFF` |
| Classes / attributes | `#FFCB6B` |
| Strings | `#80CBC4` |
| Numbers / constants | `#F77669` |
| Comments | `#A7ED87` |
| Tags | `#ff5370` |

---

## ⚙️ Recommended settings

The screenshots use [Fira Code](https://github.com/tonsky/FiraCode) with ligatures:

```json
{
	"workbench.colorTheme": "Material Base Theme",
	"editor.fontFamily": "Fira Code, Consolas, monospace",
	"editor.fontLigatures": true
}
```

---

## 🖼️ Language previews

### JSX
![JSX](https://raw.githubusercontent.com/ttnbtfy/material-base-theme/master/images/jsx.png)

### TSX
![TSX](https://raw.githubusercontent.com/ttnbtfy/material-base-theme/master/images/tsx.png)

### HTML
![HTML](https://raw.githubusercontent.com/ttnbtfy/material-base-theme/master/images/html.png)

### SCSS
![SCSS](https://raw.githubusercontent.com/ttnbtfy/material-base-theme/master/images/scss.png)

### PHP
![PHP](https://raw.githubusercontent.com/ttnbtfy/material-base-theme/master/images/php.png)

### Java
![Java](https://raw.githubusercontent.com/ttnbtfy/material-base-theme/master/images/java.png)

---

## 🤝 Feedback & contributing

Found a color that looks off, or want to tweak the theme?
[Open an issue](https://github.com/ttnbtfy/material-base-theme/issues) or send a pull request — all colors live in [`theme.json`](https://github.com/ttnbtfy/material-base-theme/blob/master/theme.json).

## 📄 License

[MIT](https://github.com/ttnbtfy/material-base-theme/blob/master/LICENSE) — free to use, modify and share.
