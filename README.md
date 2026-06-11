# WP Design Token Editor

Visual editor for WordPress `theme.json` design tokens. Edit presets and export ready-to-use code.

## Features

- **Colors** — edit the color palette with hex pickers
- **Gradients** — edit gradient presets
- **Font sizes** — edit typography scale with preset scales (Major Second, Minor Third, etc.)
- **Spacing** — edit spacing scale presets
- **Shadows** — edit box-shadow presets
- **Aspect Ratios** — edit aspect ratio presets
- **Layout** — configure `contentSize` / `wideSize`

### Export

- **theme.json** — full `settings` object ready to paste
- **CSS variables** — `--wp--preset--*` custom properties

## Usage

Open `index.html` in any browser. No build step required.

Edit tokens in the left sidebar. Preview changes in real time. Switch to the Export tab and copy the output.

## WordPress Core presets

The editor starts with the official WordPress 7.0 default presets:
- Colors (12), Gradients (12), Font sizes (6), Spacing (7), Shadows (5), Aspect Ratios (6)

## License

MIT
