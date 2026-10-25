# AFK public images

Images the AFK Slack app shows in its arcade menu. Slack loads images from a
public web address, so these three files live in this public repo.

| File | Used for |
|---|---|
| `afk-banner.png` | Banner at the top of the arcade menu (1200×400) |
| `fuse-tile.png` | FUSE game tile (512×512) |
| `ambush-tile.png` | AMBUSH game tile (512×512) |

Only images live here: no code, tokens or data. The AFK app reads them from
`AFK_ASSET_BASE_URL`, `https://raw.githubusercontent.com/Caitm99/afk-assets/main`.
