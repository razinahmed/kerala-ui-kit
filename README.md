# Kerala UI Kit

![CSS](https://img.shields.io/badge/CSS-Design-blue)
![HTML](https://img.shields.io/badge/HTML5-Components-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A modern UI component library inspired by the rich visual heritage of Kerala. This kit provides ready-to-use design tokens, color palettes, and styled components rooted in traditional Kerala aesthetics -- from temple gold to monsoon greens.

## Features

- Pre-defined CSS custom properties based on traditional Kerala color palettes
- Dark-themed base with vibrant accent colors
- Reusable component classes for buttons, cards, and layout primitives
- Lightweight with zero JavaScript dependencies
- Designed for seamless integration into any web project

## Tech Stack

| Technology | Purpose               |
|------------|-----------------------|
| CSS3       | Styling and theming   |
| HTML5      | Markup and structure  |
| Make       | Build automation      |

## Quick Start

1. Clone the repository:

```bash
git clone https://github.com/razinahmed/kerala-ui-kit.git
cd kerala-ui-kit
```

2. Include the theme in your project:

```html
<link rel="stylesheet" href="styles/theme.css" />
```

3. Use the CSS variables in your styles:

```css
.my-component {
  color: var(--primary);
  background-color: var(--background);
}
```

## Theme Variables

| Variable       | Value     | Description           |
|----------------|-----------|-----------------------|
| `--primary`    | `#00d4aa` | Primary accent color  |
| `--background` | `#1e1e2e` | Base background color |

## Build

```bash
make build
make test
```

## Project Structure

```
kerala-ui-kit/
  styles/
    theme.css       # Core theme variables
  Makefile          # Build commands
  LICENSE           # MIT License
```

## Contributing

Contributions are welcome. Please open an issue to discuss proposed changes before submitting a pull request.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
