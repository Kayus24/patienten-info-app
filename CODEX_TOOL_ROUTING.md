# Patienten-Info-App Codex Tool Routing

Applies only to **Codex**.

Inherit: `Kayus24/vibe-shared-knowledge/tool-routing/CODEX_BASELINE.md`.

## Project-specific hierarchy
1. Read `AGENTS.md`, `TOOL_ROUTING.md`, then the smallest relevant source files.
2. Use local Git, repository-native search and shell first.
3. Run the local PWA/dev server and use **Codex's own browser first** for actual UI/PWA behavior.
4. Use Developer Mode/full CDP access when approved for console, network, service-worker, cache and page-state debugging.
5. Use repository Playwright/E2E for deterministic UI/PWA regression.
6. Use local Android SDK/ADB/emulator tooling through Codex shell for device-only behavior.
7. For medical/public source verification, use official sources via Codex's own browser and record sources in the app as required.

## Hard exclusions
- Do not route Codex web research to Firecrawl by default.
- Do not inherit ChatGPT connectors such as Consensus, Firecrawl, Figma, OpenArt or Test Android Apps.
- External integrations must be explicitly configured for Codex/project use.
