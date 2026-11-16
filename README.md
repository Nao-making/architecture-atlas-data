# architecture-atlas-data

Data files for the *Architecture Atlas* iOS apps (Tokyo first; other cities later).
The apps check `data-manifest.json` at launch and download `buildings.json` when a newer version is published.

アプリ「建築マップ(Architecture Atlas)」が起動時に読み込む、建物データの置き場です。

## Files

- `tokyo/buildings.json` — building data (array of buildings)
- `tokyo/data-manifest.json` — `schemaVersion`, `dataVersion`, `count`, `sha256` of `buildings.json`

## Notes

- Compiled from public information. It may contain errors or out-of-date information.
- Photos are not included; the apps fetch them from Wikimedia Commons.
- Terms of reuse: not decided yet. Please contact the owner before reusing the data.
