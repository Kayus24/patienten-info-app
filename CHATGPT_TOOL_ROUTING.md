# Patienten-Info-App ChatGPT Tool Routing

Applies only to **ChatGPT**.

Inherit: `Kayus24/vibe-shared-knowledge/tool-routing/CHATGPT_BASELINE.md`.

## Project-specific hierarchy
- Code/repo/deploy state: GitHub.
- Medical/scientific claim discovery/synthesis: Consensus.
- Primary-source/full-text retrieval and current public source verification: Firecrawl Search/Scrape/Paper Research.
- PWA/browser API questions: Context7 -> official upstream -> Firecrawl Developer Search.
- UI regression: existing browser tests/Playwright; Firecrawl Interact only as an independent simple public-browser check.
- Device-specific PWA behavior: Test Android Apps / ADB.
- Local build/test: Remote Desktop Commander.
- Visual design mockups: Figma; generated decorative assets: OpenArt.

## Boundary
This connector/plugin hierarchy is not Codex routing.
