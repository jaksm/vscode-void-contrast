# Void Contrast

Dark High Contrast, but clean. Pure black background, zero border noise.

## What it is

A VS Code theme based on the built-in **Dark High Contrast** with one opinionated change: almost all UI borders are removed. Your code floats in the void. The UI chrome disappears.

## What stays

- ✅ Syntax highlighting — identical to Dark High Contrast
- ✅ Pure black (#000000) background
- ✅ Indent guide lines (subtle)
- ✅ Active tab top border (thin white line)
- ✅ Editor group separators (barely visible)
- ✅ Git gutter colors
- ✅ Error/warning decorations

## What's gone

- ❌ Contrast borders everywhere
- ❌ Sidebar borders
- ❌ Activity bar borders
- ❌ Tab separator borders
- ❌ Panel borders (mostly)
- ❌ Title bar borders
- ❌ Status bar borders
- ❌ Scrollbar shadows
- ❌ Overview ruler borders

## Install

```bash
# From the extension directory
code --install-extension void-contrast-0.1.0.vsix

# Or for development
ln -s /path/to/vscode-void-contrast ~/.vscode/extensions/void-contrast
```

Then: `Cmd+K Cmd+T` → select **Void Contrast**

## Build VSIX

```bash
npx @vscode/vsce package
```
