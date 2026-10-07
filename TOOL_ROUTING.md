# Patienten-Info-App Runtime Routing

Shared dispatcher: `Kayus24/vibe-shared-knowledge/tool-routing/BASELINE.md`.

## Runtime dispatch
- **ChatGPT:** read `CHATGPT_TOOL_ROUTING.md`.
- **Codex:** read `CODEX_TOOL_ROUTING.md`.

Never apply ChatGPT plugin priorities to Codex.

## Source of truth
1. This GitHub repository.
2. Claims/sources embedded in the app.
3. External research supports claims but does not override repository content without an explicit edit.

## Gates
- Keep sources coupled to claims.
- No patient-specific data.
- Medical text changes require source verification before publication.

## Directory routing
- `index.html`: main application content and UI.
- `training/**`: training-specific content/assets.
- `icons/**`: static icon assets only.
- `manifest.webmanifest` and `service-worker.js`: PWA/install/cache behavior.
- QR assets in root are deployment/navigation assets, not content source of truth.
