# Spartan Color Scheme

[![License](https://img.shields.io/github/license/renzojohnson/spartan-color-scheme.svg?style=flat-square)](https://github.com/renzojohnson/spartan-color-scheme/blob/main/LICENSE)
[![Downloads](https://img.shields.io/packagecontrol/dt/Spartan%20Color%20Scheme.svg?style=flat-square)](https://packagecontrol.io/packages/Spartan%20Color%20Scheme)
[![Latest Release](https://img.shields.io/github/release/renzojohnson/spartan-color-scheme.svg?style=flat-square)](https://github.com/renzojohnson/spartan-color-scheme/releases/latest)

A dark and light color scheme for Sublime Text with a deep purple-black background and vivid Monokai-inspired syntax highlighting. Designed for long coding sessions with high readability and minimal eye strain.

## Variants

| Variant | Background | Best For |
|---------|-----------|----------|
| **Spartan** (dark) | ![#0d0717](https://placehold.co/15x15/0d0717/0d0717.png) `#0d0717` | Low-light / night coding |
| **Spartan Light** | ![#fafafa](https://placehold.co/15x15/fafafa/fafafa.png) `#fafafa` | Bright environments / daylight |

## Preview

### Spartan (Dark)

![Spartan Dark](preview.png)

### PHP

![PHP](screenshots/php.png)

### JavaScript

![JavaScript](screenshots/javascript.png)

### CSS

![CSS](screenshots/css.png)

### HTML

![HTML](screenshots/html.png)

## Installation

### Package Control (Recommended)

1. Open Command Palette (`Cmd+Shift+P` / `Ctrl+Shift+P`)
2. Select **Package Control: Install Package**
3. Search for **Spartan Color Scheme**
4. Activate:
   - Dark: **Preferences > Color Scheme > Spartan**
   - Light: **Preferences > Color Scheme > Spartan Light**

### Manual Installation

1. Download the desired scheme files
2. Place in `Packages/User/` (Preferences > Browse Packages)
3. Activate via **Preferences > Color Scheme**

### Sublime Text < Build 3149

Use the `.tmTheme` files. Add to your settings:

```json
"color_scheme": "Packages/Spartan Color Scheme/Spartan.tmTheme"
```

## Colors (Dark)

| Role | Color | Hex |
|------|-------|-----|
| Background | ![#0d0717](https://placehold.co/15x15/0d0717/0d0717.png) | `#0d0717` |
| Foreground | ![#ffffff](https://placehold.co/15x15/ffffff/ffffff.png) | `#ffffffd9` |
| Caret | ![#ffd800](https://placehold.co/15x15/ffd800/ffd800.png) | `#ffd800` |
| Comments | ![#dddddd](https://placehold.co/15x15/dddddd/dddddd.png) | `#dddddd65` |
| Strings | ![#e6db74](https://placehold.co/15x15/e6db74/e6db74.png) | `#e6db74` |
| Keywords | ![#f92672](https://placehold.co/15x15/f92672/f92672.png) | `#f92672` |
| Functions/Classes | ![#a6e22e](https://placehold.co/15x15/a6e22e/a6e22e.png) | `#a6e22e` |
| Types/Library | ![#66d9ef](https://placehold.co/15x15/66d9ef/66d9ef.png) | `#66d9ef` |
| Numbers/Constants | ![#ae81ff](https://placehold.co/15x15/ae81ff/ae81ff.png) | `#ae81ff` |
| Parameters | ![#fd971f](https://placehold.co/15x15/fd971f/fd971f.png) | `#fd971f` |

## Colors (Light)

| Role | Color | Hex |
|------|-------|-----|
| Background | ![#fafafa](https://placehold.co/15x15/fafafa/fafafa.png) | `#fafafa` |
| Foreground | ![#2d2d2d](https://placehold.co/15x15/2d2d2d/2d2d2d.png) | `#2d2d2d` |
| Comments | ![#6e6e6e](https://placehold.co/15x15/6e6e6e/6e6e6e.png) | `#6e6e6e` |
| Strings | ![#8a7020](https://placehold.co/15x15/8a7020/8a7020.png) | `#8a7020` |
| Keywords | ![#c4166a](https://placehold.co/15x15/c4166a/c4166a.png) | `#c4166a` |
| Functions/Classes | ![#487000](https://placehold.co/15x15/487000/487000.png) | `#487000` |
| Types/Library | ![#14707e](https://placehold.co/15x15/14707e/14707e.png) | `#14707e` |
| Numbers/Constants | ![#7040c0](https://placehold.co/15x15/7040c0/7040c0.png) | `#7040c0` |
| Parameters | ![#a85a00](https://placehold.co/15x15/a85a00/a85a00.png) | `#a85a00` |

## Plugin Compatibility

Spartan includes dedicated scopes for these popular Sublime Text plugins:

- **[GitGutter](https://packagecontrol.io/packages/GitGutter)** — colored gutter marks for insertions, deletions, and changes
- **[BracketHighlighter](https://packagecontrol.io/packages/BracketHighlighter)** — per-bracket-type coloring (curly, round, square, angle, tag, quote)
- **[SublimeLinter](https://packagecontrol.io/packages/SublimeLinter)** — error, warning, and info mark colors (SublimeLinter 4+)

## Supported Languages

Full syntax coverage for PHP, JavaScript, TypeScript, HTML, CSS, LESS, Sass/SCSS, JSON, YAML, Markdown, SQL, Python, Shell/Bash, CoffeeScript, Makefile, Twig, Handlebars, and all languages using standard TextMate scopes.

## Credits

- **Author**: [Renzo Johnson](https://renzojohnson.com)
- **License**: MIT
