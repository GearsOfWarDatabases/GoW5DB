# Character Images

Two JPGs per character/skin, named by slug, listed in `_data/characters.yml`:

- `<slug>.jpg` - body crop, no UI/menu chrome (fractional box `0.31, 0.0,
  0.64, 0.90` of the 1920x1080 source). Used as the large image under each
  entry on the Characters page.
- `<slug>-portrait.jpg` - head/shoulders crop (fractional box `0.33, 0.02,
  0.63, 0.36`). Used as the small round avatar next to the name.

Both are a single fixed crop applied to every source screenshot, not a
per-character manual crop - good enough for a list/grid, but taller or
oddly-posed models (bosses especially) can end up a little off-center in
the portrait crop. Re-crop by hand if a specific character needs a tighter
frame.

Some source screenshots show a faint watermark (e.g. the character's name)
baked into the 3D render for locked characters - that's what the game
itself displays, not a cropping mistake.
