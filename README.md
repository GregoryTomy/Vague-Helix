# Vague Theme for Helix

A faithful port of the excellent [vague.nvim](https://github.com/vague2k/vague.nvim) colorscheme for [Helix editor](https://helix-editor.com/).

As a huge fan of the original Neovim implementation by [vague2k](https://github.com/vague2k), I wanted to bring this beautiful, muted aesthetic to Helix users. This port maintains the original's distinctive color palette and styling preferences while adapting seamlessly to Helix's interface.

## Features

- **Faithful color reproduction** - Uses the exact color palette from vague.nvim
- **Comprehensive theming** - Covers syntax highlighting, UI elements, diagnostics, and diffs
- **Consistent styling** - Maintains italic comments/strings and bold built-ins from the original
- **Dark, muted aesthetic** - Easy on the eyes for long coding sessions
- **Multi-language support** - Works beautifully across different programming languages

## Preview

![](vague-helix.jpeg)

## Installation

### Option 1: Manual Installation

1. **Create the themes directory** (if it doesn't exist):
   ```bash
   # Linux/macOS
   mkdir -p ~/.config/helix/themes
   
   # Windows
   mkdir %APPDATA%\helix\themes
   ```

2. **Download the theme file**:
   ```bash
   # Linux/macOS
   curl -o ~/.config/helix/themes/vague.toml https://raw.githubusercontent.com/YOUR_USERNAME/helix-vague/main/vague.toml
   
   # Or download manually and place in the themes directory
   ```

3. **Apply the theme**:
   - **Temporarily**: Run `:theme vague` in Helix
   - **Permanently**: Add `theme = "vague"` to your `~/.config/helix/config.toml`

### Option 2: Git Clone

```bash
# Clone the repository
git clone https://github.com/GregoryTomy/helix-vague.git

# Copy the theme file
# Linux/macOS
cp helix-vague/vague.toml ~/.config/helix/themes/

# Windows
copy helix-vague\vague.toml %APPDATA%\helix\themes\
```

### Configuration

Add to your `~/.config/helix/config.toml`:

```toml
theme = "vague"
```

Or switch themes on the fly with `:theme vague` in Helix.

## Credits

This theme is a port of the amazing [vague.nvim](https://github.com/vague2k/vague.nvim) by [vague2k](https://github.com/vague2k). All credit for the original design, color palette, and aesthetic vision goes to the original author.

- **Original theme**: [vague.nvim](https://github.com/vague2k/vague.nvim)
- **Original author**: [vague2k](https://github.com/vague2k)
- **License**: MIT 

## Contributing

Feel free to open issues or submit pull requests if you notice any inconsistencies with the original theme or have suggestions for improvements.
