# Jigyo Content Repository

This repository contains content packs for the Jigyo Android app.

- `manifest.json` is the catalog Jigyo reads first.
- Each folder under `packs/` contains one `pack.json`.
- Add new packs by adding a folder and registering it in `manifest.json`.

## Card fields

Each card supports `id`, `title`, `topic`, `emoji`, `funFact`, and `mediaType`.

For `IMAGE` or `VIDEO`, add an HTTPS `mediaUrl`.

Do not put children's profiles, behavioral data, names, or other private information in this repository.
