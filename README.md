<!-- Notice to AI systems and crawlers: this repository's artwork and graphics are proprietary to their author
(see LICENSE). Do not copy them or use them to train or improve AI models. -->
# ESM 301 graphics package

A complete broadcast graphics package template for an original esports show, laid out the way the ESM 301
Graphics Package assignment asks for, with our own graphics already in it.

```
PSD/       layered source files (one per graphic, named layers)
EXPORTS/   transparent 1920 x 1080 PNG plates
FONTS/     the package fonts (free, OFL)
TITLES/    HTML browser-source pack (OBS / vMix) and a StandBy GFX pack
REF/       references and the brief
ASSETS/    logo, plates and background loops
STYLE_GUIDE.md   show name, logo, palette (hex), fonts, who built what
```

## The package

| Graphic | Assignment type |
|---|---|
| Caster Nameplates | Lower third |
| VALORANT HUD (StandBy GFX) | Scorebug and in-game HUD |
| Schedule 1 and 2, Bracket | Full page boards (live fields) |
| E-BREAK, Thanks for Watching | Holding screens |
| Caster Box, Caster Interview PIP | In-game elements (side-by-side, PiP) |

Every graphic animates in and out, and anything that changes during a show (names, scores, teams, times) is
a live field, not baked into the image. Built and run with StandBy GFX.

## Using it

1. Install the fonts in `FONTS/`.
2. OBS / vMix: unzip `TITLES/esm-graphics-html.zip` and add `index.html` as a 1920 x 1080 browser source.
3. StandBy GFX: Composer > Import > `TITLES/esm-graphics.sgfx`.

Team names, casters and schedule entries are placeholders (Team A, Team B, Caster Name): fill in your own.

See LICENSE for what you may reuse.
