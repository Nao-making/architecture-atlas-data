# architecture-atlas-data

Data files for the *Architecture Atlas* iOS apps (Tokyo, London and Rome so far; other cities later).
The apps check `data-manifest.json` at launch and download `buildings.json` when a newer version is published.

アプリ「建築マップ(Architecture Atlas)」が起動時に読み込む、建物データの置き場です。

## Files

- `tokyo/buildings.json` — building data (array of buildings)
- `tokyo/data-manifest.json` — `schemaVersion`, `dataVersion`, `count`, `sha256` of `buildings.json`
- `london/buildings.json`, `london/data-manifest.json` — the same, for London
- `rome/buildings.json`, `rome/data-manifest.json` — the same, for Rome

## Notes

- Compiled from public information. It may contain errors or out-of-date information.
- Photos are not included; the apps fetch them from Wikimedia Commons.
- Terms of reuse: not decided yet. Please contact the owner before reusing the data.
