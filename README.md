# Claude Theme

A warm, elegant color theme inspired by Claude's aesthetic. Available for VS Code and Ghostty terminal.

## Features

- Warm, eye-friendly color palette based on Claude's UI
- No blue colors - uses warm amber and teal alternatives
- Both light and dark variants
- Consistent colors across VS Code and Ghostty terminal

## Color Palette

| Role | Light | Dark |
|------|-------|------|
| Background | `#FFFCF9` | `#282320` |
| Foreground | `#1F1D1B` | `#F5F1ED` |
| Accent | `#D97757` | `#D97757` |
| Functions | `#B8860B` | `#E9A23B` |
| Types | `#3D8B80` | `#5EADA4` |
| Strings | `#059669` | `#34D399` |
| Keywords | `#D97757` | `#D97757` |

## VS Code Installation

### Option 1: Symlink (recommended)

```bash
# macOS/Linux
ln -s /path/to/claude-theme ~/.vscode/extensions/claude-theme

# Windows (PowerShell as Admin)
New-Item -ItemType SymbolicLink -Path "$env:USERPROFILE\.vscode\extensions\claude-theme" -Target "C:\path\to\claude-theme"
```

### Option 2: Copy

```bash
# macOS/Linux
cp -r /path/to/claude-theme ~/.vscode/extensions/

# Windows
xcopy /E /I "C:\path\to\claude-theme" "%USERPROFILE%\.vscode\extensions\claude-theme"
```

### Activate

1. Open VS Code
2. Press `Cmd+K Cmd+T` (macOS) or `Ctrl+K Ctrl+T` (Windows/Linux)
3. Select **Claude Light** or **Claude Dark**

## Ghostty Installation

```bash
# Create themes directory
mkdir -p ~/.config/ghostty/themes

# Copy theme files
cp ghostty/claude-light ~/.config/ghostty/themes/
cp ghostty/claude-dark ~/.config/ghostty/themes/
```

Add to `~/.config/ghostty/config`:

```
theme = claude-dark
```

Restart Ghostty to apply.

## License

MIT License - see [LICENSE](LICENSE) for details.
