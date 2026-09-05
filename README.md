# Melody · 減脂進度

Personal fitness / diet dashboard for Melody.

**Site:** https://melodycheng622-cmyk.github.io/

This is a GitHub Pages site. Open the URL on phone or desktop to view the live dashboard (`本週` / `每週檔案` / `逐筆紀錄`).

## Files

| Path | What |
|---|---|
| `index.html` | Interactive dashboard |
| `data/fitness_food_log.xlsx` | Canonical food / body / training workbook |
| `data/fitness_food_log.csv` | CSV export (may be stale vs xlsx) |
| `data/fitness_food_log.md` | Markdown export (may be stale vs xlsx) |
| `data/fitness_food_log_spec.json` | Log field spec |
| `snapshots/` | Static PNG captures for Discord |

Workbook is the source of truth. Dashboard is a read-only view.

## Privacy

Contains personal weight, BIA, training, and calorie logs. `robots.txt` asks search engines not to index. The repository is public because GitHub Pages on a free account requires a public repo.
