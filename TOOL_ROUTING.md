# Patienten-Info-App Tool Routing

Inherit: `Kayus24/vibe-shared-knowledge/tool-routing/BASELINE.md`.

## Source of truth
1. This GitHub repository
2. Claims/sources embedded in the app
3. External research supports claims but does not override repository content without an explicit edit

## Preferred hierarchy
- Code/repo/deploy state: **GitHub**
- Medical/scientific claim research: **Consensus**
- Public source verification/extraction: **Firecrawl**
- PWA/browser API questions: **Context7**
- UI regression: existing browser tests/Playwright; **Firecrawl Interact** only for a small external-browser check
- Device-specific PWA behavior: **Test Android Apps/ADB**
- Local build/test: **Remote Desktop Commander**
- Visual design mockups: **Figma**; generated decorative assets: **OpenArt**

## Gates
- Keep sources coupled to claims.
- No patient-specific data.
- Medical text changes require source verification before publication.
## Directory routing
- `index.html`: main application content and UI.
- `training/**`: training-specific content/assets; keep separate from general waiting-room information.
- `icons/**`: static icon assets only.
- `manifest.webmanifest` and `service-worker.js`: PWA/install/cache behavior; touch only for PWA-specific tasks and test accordingly.
- QR assets in root are deployment/navigation assets, not content source of truth.
