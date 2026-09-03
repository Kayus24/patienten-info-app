# Canonical Exercise Asset Catalog — V1

Only files in this folder are canonical for the training page. Do not fall back to legacy `training/assets/*.svg`, sprites, embedded base64 assets, or older recovery folders.

| Exercise | Canonical file |
|---|---|
| Bizeps Curls | `biceps-curls.webp` |
| Rudern | `rowing.webp` |
| Trizeps-Maschine aufgelegt | `triceps-machine.webp` |
| Bankdrücken | `bench-press.webp` |
| Fliegende | `chest-fly.webp` |
| Schulterdrücken | `shoulder-press.webp` |
| Seitheben | `lateral-raise.webp` |
| Latzug | `lat-pulldown.webp` |
| Kurzhantel-Rudern | `dumbbell-row.webp` |
| Beinpresse | `leg-press.webp` |
| Kniestrecker | `leg-extension.webp` |
| Deadlift | `deadlift.webp` |
| Kniebeuger | `leg-curl.webp` |
| Plank | `plank.webp` |
| Beinheben | `leg-raise.webp` |

## Regression guard
A website change is invalid if any training card references an asset outside `assets/canonical-v1/`, except non-exercise UI assets. Changes to an approved exercise image require explicit replacement of the matching canonical file and update of this catalog if the filename changes.
