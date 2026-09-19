# Jigyo v12 Content Packs

Upload these files to the root of `jnarayan81/Jigyo`.

Each schema-v2 card contains topic/subtopic metadata, age bands, tags, difficulty,
estimated viewing time, an interaction mode, and declarative animation metadata.

`mediaType: EMOJI` means the packs work immediately without external media.
The `animation` and `reveal` objects are forward-compatible presentation metadata:
Jigyo v12 must render these fields for the animations to appear; older clients can
ignore unknown fields safely.

When adding IMAGE/VIDEO cards, use HTTPS `mediaUrl` and `thumbnailUrl` fields and
only publish media you have the rights to distribute.
