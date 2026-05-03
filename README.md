# Nightshift brand assets

This repository is a public mirror of the brand artifacts
(logo, animated hero, custom emoji) shipped by the
Nightshift Slack app.  The source repository is private;
this mirror exists solely so Slack's `image` blocks can
fetch the assets over public HTTPS without authentication.

Updates land here automatically via a GitHub Action in
the source repo on every change to a whitelisted file.

## Files

| Path | Purpose |
|---|---|
| `icons/nightshift_logo.png`  | Slack app icon (512×512 PNG, ~232 KB) |
| `icons/nightshift_emoji.gif` | Animated `:nightshift:` workspace emoji (128×128, ~55 KB) |
| `home/nightshift_hero_wide.png` | Static App Home hero (1536×384 PNG) |
| `home/nightshift_hero_anim.gif` | Animated App Home hero (1536×384 GIF, ~950 KB) |

## Licensing

All artwork in this repository is owned by Tenet Security and
generated in-house for the Nightshift product.  Hot-linking
for the published Slack app is the intended use; please do not
re-use these assets in unrelated projects.
