# Black Dracula

A beautiful dark VS Code theme featuring the Dracula color palette with a pitch-black background (#000000).

## Features

- **Dracula Colors**: All the vibrant Dracula syntax colors you love
- **Pitch-Black Background**: A true black (#000000) background instead of Dracula's default dark gray (#282a36)
- **High Contrast**: Excellent readability with careful color pairing
- **Complete Coverage**: Full support for all UI elements, syntax highlighting, terminal colors, and semantic tokens
- **Consistent Design**: Cohesive color scheme across editor, sidebar, status bar, and terminal

## Installation

1. Open VS Code
2. Go to **Extensions** (Ctrl+Shift+X / Cmd+Shift+X)
3. Search for "Black Dracula"
4. Click **Install**
5. Open Command Palette (Ctrl+Shift+P / Cmd+Shift+P)
6. Type "Color Theme" and select **Black Dracula**

Or install from the command line:
```bash
code --install-extension user.black-dracula
```

## Color Palette

| Element | Color | Hex |
|---------|-------|-----|
| Background | Pitch Black | #000000 |
| Foreground | White | #f8f8f2 |
| Comments | Slate | #6272a4 |
| Strings | Yellow | #f1fa8c |
| Numbers | Purple | #bd93f9 |
| Keywords | Pink | #ff79c6 |
| Types/Storage | Cyan | #8be9fd |
| Functions/Classes | Green | #50fa7b |
| Parameters | Orange | #ffb86c |
| Errors | Red | #ff5555 |

## Customization

You can customize the theme by modifying colors in your VS Code `settings.json`:

```json
{
  "workbench.colorCustomizations": {
    "[Black Dracula]": {
      "editor.background": "#0a0a0a",
      "editor.foreground": "#f8f8f2"
    }
  },
  "editor.tokenColorCustomizations": {
    "[Black Dracula]": {
      "comments": "#6272a4"
    }
  }
}
```

## Development

This theme extends the official Dracula theme with a pure black background for improved contrast and reduced eye strain in dark environments.

## License

MIT License - See LICENSE file for details

## Credits

Based on the [Dracula Theme](https://draculatheme.com/) by Zeno Rocha and the Dracula community.
