# Golf Breeze remote config

`config.json` is read by the Golf Breeze app at launch (cached on the device; the app works without it).

- `courses[].enabled: false` switches a course off: its card reads the `notice` (default "Greens currently under repair")
  and PLAY falls back to Breeze Island.
- `courses[].fallbackHoles: [7]` replaces those holes in a round with a simple safe version of the hole.
- `message` is shown once on the home screen when non-empty.

Nothing here affects prices or purchases.
