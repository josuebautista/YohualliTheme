# 🌙 Yohualli Theme for VSCode

**Yohualli** — the Nahuatl word for *night* — is a collection of **four carefully crafted themes** that evoke the mystique of the moon and the calm of the night sky. Each variant draws inspiration from a different celestial concept: **Nebulune**, **Eclipse**, **Lunaris**, and **Penumbra**.

These themes deliver a smooth and modern development experience, perfect for long coding sessions with minimal eye strain.

---

## ✨ Features

- 🎨 **4 unique themes**:
  - 🌌 **Nebulune** – mystical and ethereal  
  - 🌗 **Eclipse** – bold and dramatic  
  - 🌙 **Lunaris** – soft and dreamy  
  - 🌫️ **Penumbra** – subtle and elegant  

- 💻 **Language support for**:
  - HTML, CSS, JavaScript, TypeScript
  - Python, Java, C, and C++
  - Config files: JSON, YAML, TOML, XML
  - Markdown and documentation

- ⚙️ **Framework & technology support**:
  - React, Angular, Astro, and more

---

## 🌈 Color Palette

Each theme defines:

- **Primary colors**: variables, properties, keywords, methods/functions  
- **Secondary colors**: types, parameters, generics, imports/aliases  
- **Support colors**: strings, comments, interpolations, classes, numbers

> You can explore the complete color definitions inside each theme’s JSON file.

---

## 📸 Screenshots (TODO)

- [Nebolune](./assets/nebulune-preview.jpg) Nebulune  
- [Eclipse](./assets/eclipse-preview.jpg) Eclipse
- [Lunaris](./assets/lunaris-preview.jpg) Lunaris
- [Penumbra](./assets/penumbra-preview.jpg) Penumbra

---

## ⚙️ Recommended Settings

To get the most out of this theme, install the fonts:

- Font: [Victor Mono](https://rubjo.github.io/victor-mono/) with ligatures enabled
- Font: [Iosevka](https://typeof.net/Iosevka/) 
or the nerd font version (highly recommended)...
- Font: [Victor Mono Nerd Font](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/VictorMono) with ligatures enabled
- Font: [IosevkaTerm Nerd Font](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/IosevkaTerm) designed for terminal use

```json
"editor.fontFamily": "VictorMono Nerd Font",
"editor.fontLigatures": true,
"editor.fontWeight": "400",
"editor.fontSize": 15,
"editor.lineHeight": 1.5,
"editor.wordWrap": "on",
"editor.padding.top": 5,
"editor.scrollbar.verticalScrollbarSize": 8,
"editor.scrollbar.horizontalScrollbarSize": 8,
"editor.semanticHighlighting.enabled": true,
"editor.guides.indentation": true,
"editor.cursorBlinking": "expand",
"editor.cursorSmoothCaretAnimation": "explicit",
// Optional terminal settings
"terminal.integrated.fontFamily": "IosevkaTerm Nerd Font",
"terminal.integrated.fontWeight": "400",
"terminal.integrated.fontSize": 15,
// Very very very optional UI settings (Minimal lookstyle)
"editor.minimap.enabled": false,
"editor.glyphMargin": false,
"editor.overviewRulerBorder": false,
"editor.hideCursorInOverviewRuler": true,
"editor.guides.indentation": true,
"editor.lightbulb.enabled": "off",
"editor.selectionHighlight": true,
"editor.renderLineHighlight": "all",
"editor.occurrencesHighlight": "off",
"workbench.navigationControl.enabled": false,
"workbench.editor.editorActionsLocation": "hidden", // only if you now how to navigate with shortcuts
"workbench.layoutControl.enabled": false,
"breadcrumbs.enabled": false,
"workbench.editor.showTabs": "none",
"workbench.editor.enablePreviewFromQuickOpen": false,
"workbench.tips.enabled": false,
"workbench.editor.enablePreview": false,
"workbench.startupEditor": "none",
"workbench.statusBar.visible": true,
"workbench.sideBar.location": "right",
"workbench.tree.enableStickyScroll": true,
```
No way! it's nvim

---

## 🚀 Installation

1. Launch VSCode and open this extension in development mode.
2. Press `F5` to open a new VSCode window with your extension loaded.
3. Open the color theme picker via:
   - `File > Preferences > Theme > Color Theme`, or  
   - `Preferences: Color Theme` command (`Ctrl+K Ctrl+T`)
4. Select one of the Yohualli themes.
5. Open a file with a supported language (e.g., `.js`, `.html`, `.py`, etc.).
6. To inspect how your tokens are being highlighted, use:  
   `Developer: Inspect Editor Tokens and Scopes`  
   (accessible from `Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).

---

## 📜 License

MIT © 2025 — Created with 🌙 by Alejandro Hernandez
