# 🌌 EndeavourOS Dark & Dark+ - VS Code Theme

[![Build and Test](https://github.com/jordojordo/endeavouros-vscode-theme/actions/workflows/publish.yaml/badge.svg)](https://github.com/jordojordo/endeavouros-vscode-theme/actions/workflows/publish.yaml)
[![Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/jordojordo.endeavouros-dark?label=Marketplace)](https://marketplace.visualstudio.com/items?itemName=jordojordo.endeavouros-dark)
[![Downloads](https://img.shields.io/visual-studio-marketplace/d/jordojordo.endeavouros-dark)](https://marketplace.visualstudio.com/items?itemName=jordojordo.endeavouros-dark)

![Theme Icon](themes/assets/icons/eos-icon.png)

A **VS Code theme** inspired by the **EndeavourOS KDE Breeze Dark** theme.

## Theme Variants

This extension provides **two** dark theme variants:

1. **EndeavourOS Dark** – A close match to EndeavourOS’ KDE Breeze Dark.
2. **EndeavourOS Plus** – An emulated version of the EndeavourOS Konsole theme.
3. **EndeavourOS Dark High Contrast** – A high contrast version of the EndeavourOS Dark theme.
4. **EndeavourOS Dark Night Shift** – A night shift version of the EndeavourOS Dark theme (suitable for blue light filters).

## Screenshots

### EndeavourOS Dark

![EndeavourOS Dark](themes/assets/screenshots/eos-dark.png)

### EndeavourOS Plus

![EndeavourOS Plus](themes/assets/screenshots/eos-plus.png)

### EndeavourOS Dark High Contrast

![EndeavourOS Dark High Contrast](themes/assets/screenshots/eos-dark-high-contrast.png)

## Installation

### From the VS Code Marketplace

1. Open **VS Code**.
2. Go to **Extensions** (`Ctrl + Shift + X` || `Cmd + Shift + X`).
3. Search for **EndeavourOS Dark**.
4. Click **Install**.

### Manually

1. Download the latest `.vsix` file from the [Releases](https://github.com/jordojordo/endeavouros-vscode-theme/releases) page.
2. Open **VS Code** and run:
   ```sh
   code --install-extension endeavouros-dark-<version>.vsix
   ```

## Known Issues

When using the Night Shift variant, the editor bracket colorization may be overridden by [the default settings](https://code.visualstudio.com/docs/reference/default-settings). To fix this, add the following to your `settings.json`:

```json
// Controls whether each bracket type has its own independent color pool.
"editor.bracketPairColorization.independentColorPoolPerBracketType": true
```

## Contributions

Contributions are welcome! If you have any suggestions or issues, please open an issue or a pull request.
