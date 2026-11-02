# ascii-water

Two animated backgrounds drawn entirely out of shimmering letters and numbers. Each is a single HTML file with no dependencies.

**Live:** https://matchamillefeuille.github.io/ascii-water/

## ascii-ripple.html

Dim text fills the screen. Click anywhere and a ripple of water spreads out, lighting up the characters as it passes. Ripples bend, bounce off the edges and overlap like real water. About 1 in 3 clicks sends out a heart instead.

- **Click:** make a ripple
- **Shift-click:** always make a heart

**Other colours:** add them to the link as hex codes without the `#`. For example, the green version is [`ascii-ripple.html?ink=238B45`](https://matchamillefeuille.github.io/ascii-water/ascii-ripple.html?ink=238B45). `ink` sets the text colour and `bg` sets the background, such as `?ink=C7E9C0&bg=005A32`.

## ascii-knot.html

A thick 3D knot, shaded with letters, slowly turning.

## Run it

Download or clone the repo and double-click either file to open it in a browser. Press Ctrl+Cmd+F (Mac) or F11 (Windows) for full screen.

## Tweak it

The settings sit at the top of each file's script, each with a comment. The ones worth trying in `ascii-ripple.html`:

| Setting | What it does |
| --- | --- |
| `--ink`, `--bg` (in the CSS) | Text and background colours |
| `BASE` | How visible the resting text is |
| `PEAK` | How bright ripple crests get |
| `STEPS_PER_SEC` | Ripple speed |
| `DAMPING` | How long ripples last (lower = shorter) |
| `SPEED_VARY` | How uneven the water is |
| `SHEEN` | How strongly wave slopes catch the light |
| `WOBBLE` | How much the picture sways |
| `HEART_CHANCE` | Share of clicks that make a heart (0 to 1) |
| `CHURN` | How fast the resting characters change |
