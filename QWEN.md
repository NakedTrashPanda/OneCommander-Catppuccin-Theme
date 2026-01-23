# OneCommander-Catppuccin-Theme

## Project Overview

OneCommander-Catppuccin-Theme is a custom theme for the OneCommander file manager application. It implements the popular Catppuccin color palette, specifically the Mocha flavor with Mauve accents, providing a cohesive and aesthetically pleasing dark theme experience.

The project consists of:
- XAML theme definition files that control the visual appearance
- Custom folder icons using the Catppuccin color scheme
- Resource files for enhanced visual elements

## Architecture

The theme follows OneCommander's theme structure with two main directories:

### Themes Directory
- Contains the main XAML theme file (`Catppuccin.xaml`)
- Defines all color brushes, styles, and visual elements
- Includes configurations for various UI components like:
  - File panels and navigation
  - Sidebar and favorites
  - Tabs and headers
  - Buttons and controls
  - Scrollbars and overlays

### Resources Directory
- Contains custom folder icons in the Catppuccin color palette
- Includes both standard sizes and 16px versions for different contexts
- Features a main folder icon for the theme

## Installation

To install this theme:

1. Copy both the "Themes" and "Resources" folders
2. Paste them in the root of your OneCommander installation directory
3. To find the OneCommander root folder:
   - Open OneCommander
   - Click "About Me" located at the bottom left next to settings
   - Click "Exe location"

## Customization

The theme offers some customization options:

- Accent color can be adjusted in `Catppuccin.xaml` at line 56 under "AccentBrushForced"
- Deleting the "AccentBrushForced" line allows changing colors through OneCommander's interface
- Various UI elements can be fine-tuned by modifying the XAML values

## Color Palette

The theme uses the Catppuccin Mocha palette with Mauve accents:
- Background: #11111b (crust)
- Surface: #1e1e2e (surface0)
- Text: #cdd6f4 (text)
- Accent: #cba6f7 (mauve)
- Blue: #89b4fa (blue)

## Building and Running

This is a theme distribution project that doesn't require compilation. Simply copy the files to your OneCommander directory to apply the theme.

## Development Conventions

- XAML files follow OneCommander's theme specification
- Color values use the Catppuccin palette hex codes
- Icon resources maintain consistent styling across sizes
- Documentation follows standard markdown formatting

## Contributing

The project welcomes contributions for additional Catppuccin flavors and style improvements. Contributors can:
- Add new theme variants (Latte, Frappé, Macchiato)
- Improve existing color schemes
- Enhance icon sets
- Update documentation

## License

This project is licensed under the MIT license.