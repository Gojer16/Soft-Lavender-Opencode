# Soft Lavender Themes for OpenCode

A family of hand-crafted themes for [OpenCode AI](https://opencode.ai). Built around soft purples with complementary accent palettes — each variant has its own personality while sharing the same visual DNA.

## Themes

### Soft Lavender
Deep violet backgrounds with lavender accents and warm highlights.

- **Dark background:** `#16111F`
- **Primary accent:** `#CFAEFF` / `#8E6FF7`
- **Highlights:** Rose (`#F07A9A`), peach (`#FFB38A`), gold (`#F7D98B`), mint (`#97E6B8`)

### Soft Lavender Light
Bright, airy lavender on near-white. Same accent palette, elevated for light mode.

- **Background:** `#FBF8FF`
- **Primary accent:** `#9B7BE8`
- **Highlights:** Rose, apricot, gold, mint, lilac

### Soft Lavender Cream
Warm cream base with soft lavender mids. Accents shift to warm neutrals — honey, peach, sage.

- **Background:** `#FFFDF8`
- **Primary accent:** `#A789D8`
- **Highlights:** Peach (`#D98B65`), honey (`#B98A2F`), sage (`#5AA07D`), plum

### Soft Lavender Rose
Blush pink tones throughout. Berry and coral replace the warmer accents. Most playful of the four.

- **Background:** `#FFF8FB`
- **Primary accent:** `#BD84D8`
- **Highlights:** Berry (`#C95D8E`), coral (`#DE8B7A`), amber (`#C0903D`), violet

## Features

- **Full dark + light mode** support in a single file
- **Syntax highlighting** for all major languages
- **Markdown rendering** styled consistently (headings, links, code blocks, lists)
- **Diff / git integration** with distinct added/removed highlighting and line numbers
- **Semantic color roles** — primary, secondary, accent, error, warning, success, info

## Usage

### Applying the Theme

Type `/theme` in OpenCode AI and select a variant from the list.

Or add it to your `opencode.json` config:

```json
{
  "$schema": "https://opencode.ai/config.json",
  "theme": "your-theme-name"
}
```

Replace `your-theme-name` with the filename of any theme in your themes directory (without `.json`).

### Theme Variants

| Theme | Description |
|---|---|
| `soft-lavender` | Deep violet — warm, cozy dark mode |
| `soft-lavender-light` | Bright lavender on near-white |
| `soft-lavender-cream` | Warm cream base with honey and sage accents |
| `soft-lavender-rose` | Blush rose tones — most playful variant |

Theme selections persist across sessions.

> **Note:** These usage instructions apply to any OpenCode theme — not just this repo. Any theme file placed in `~/.config/opencode/themes/` becomes available via `/theme` and the config above.

## Installation

### Global Installation

Create the themes directory and download all four variants:

```bash
mkdir -p ~/.config/opencode/themes

curl -o ~/.config/opencode/themes/soft-lavender.json https://raw.githubusercontent.com/Gojer16/Soft-Lavender-Opencode/main/.opencode/themes/soft-lavender.json

curl -o ~/.config/opencode/themes/soft-lavender-light.json https://raw.githubusercontent.com/Gojer16/Soft-Lavender-Opencode/main/.opencode/themes/soft-lavender-light.json

curl -o ~/.config/opencode/themes/soft-lavender-cream.json https://raw.githubusercontent.com/Gojer16/Soft-Lavender-Opencode/main/.opencode/themes/soft-lavender-cream.json

curl -o ~/.config/opencode/themes/soft-lavender-rose.json https://raw.githubusercontent.com/Gojer16/Soft-Lavender-Opencode/main/.opencode/themes/soft-lavender-rose.json
```

That's it. The themes will be available globally in OpenCode AI.

### Manual

Copy any theme file into your OpenCode themes directory:

```
~/.config/opencode/themes/
```

## File Structure

```
~/.config/opencode/themes/
├── soft-lavender.json        # Deep violet (dark/warm)
├── soft-lavender-light.json  # Bright lavender on white
├── soft-lavender-cream.json  # Warm cream + lavender mids
└── soft-lavender-rose.json   # Blush rose variant
```

## License

See [LICENSE](LICENSE) — MIT, do whatever.
