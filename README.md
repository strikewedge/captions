# Social caption system

Caption overlay builder for Strike Wedge reels and shorts.

Type a headline, pick a layout and a colour, download it as a transparent
1080 x 1920 PNG, and drop it over the clip in CapCut, Premiere or Canva.

**Live: https://strikewedge.github.io/captions**

- Six layouts: Stacked, Highlight block, Kicker, Full colour, Stacked smaller (same face as A, sized so two words fit on a line), and Brand toolkit headline (Work Sans Bold, all caps, tracking -5%, line height 0.9, the main heading style from the brand toolkit).
- Caps toggle: on renders A, B, D, E and F uppercase; off renders the line as typed. Kicker stays sentence case.
- Centre toggle: centres every line in the middle of the frame (preview and export), for lines like a sale headline with the offer underneath.
- Text and accent colour picked from the brand palette (beige, lilac, orange, green).
- Backdrop switcher (turf, dark, bright) to check contrast before committing. Preview only, never exported.
- Wrap a word in asterisks to make it the accent word, e.g. `Never *scoop* the ball again`.
- Press Enter in the headline box to break a line exactly where you want it. Anything still too wide for the text box wraps on its own.
- Safe zones show the Reels and TikTok interface margins: top 250px, bottom 420px, sides 60px.

Everything is in `index.html`. Fonts (Work Sans, IBM Plex Mono) are embedded, so
it works offline and has no external dependencies.

The brand rules behind it live in the knowledge base at `brand/visual.md`
(repo `strikewedge/sw-knowledge`).
