# Borozdov Easel

A theme from the Borozdov collection. Two faces — light **Underpaint**, a designer's white
studio, and dark **Varnish**, the same studio after the final coat. Black ink, hairline
cards and one decisive blue mark for what matters.

![Borozdov Easel in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/easel/main/screenshots/light.png)

![Borozdov Easel in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/easel/main/screenshots/dark.png)

## Principles

- **Black ink, chiseled display.** Headings run from weight 500 to 600 and tighten their
  tracking as they grow; body and UI text stay a plain, open 400.
- **White studio floor, hairline cards.** A near-white grey scale throughout; cards sit on
  paper white behind a hairline border.
- **One decisive blue.** The main button, a checked task, a toggle, links, the open file
  and the highlighter all share the same saturated blue — no second accent competes with
  it.
- **Square studio shapes.** 4px corners on fields, tags and buttons, 8px on cards — a
  drafting tool, not a pillow.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- The open file marked in the one blue, in the file explorer
- The highlighter as an opaque blue mark, tuned separately per face so it never turns
  muddy at night
- Callouts as white cards with the title in the type's colour; the plain note rests on the
  blue wash
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No embedded fonts, so the theme stays under 13 KB
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Utility**. Install Borozdov Utility under Settings → Appearance → Themes → Manage, then
the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and
choose **Easel** under Style Settings → Borozdov Utility → Variant. The variant brings
this theme's palette, type and corners; its own layout, and its embedded font if it has
one, come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the [latest
release](https://github.com/borozdov-obsidian-themes/easel/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Easel/`, then choose Borozdov Easel under Settings →
Appearance → Themes.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Underpaint» — белая студия
дизайнера, и тёмный «Varnish» — та же студия после последнего слоя лака. Чёрные чернила,
карточки на тонкой линии и один решительный синий для того, что важно. Шрифты не встроены.
В каталоге тема живёт вариантом Borozdov Utility: установите Borozdov Utility и плагин Style Settings, затем выберите Easel в Style Settings → Borozdov Utility → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
