# beamer — présentation Beamer

Feuille de présentation (class `beamer`). Madrid theme, seahorse/dolphin
colour themes, footer branding. Basé sur latex-templates.

## Contents

| Document | Kind | Notes |
| --- | --- | --- |
| `src/beamer_main.tex` | Présentation (`beamer`) | Title page, outline frame, theme frame. |

## Use

```sh
latex_handler new ma_presentation --template beamer
cd ma_presentation
latex_handler compile --file src/beamer_main.tex
```

See `examples/README.md` for compile commands.
