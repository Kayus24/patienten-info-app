# AGENTS.md

- Treat this repository as the project boundary.
- Read `README.md` and `TOOL_ROUTING.md` before substantial work.
- Use the source-of-truth, directory routing and gates in `TOOL_ROUTING.md`.
- If the active runtime is **Codex**, read `CODEX_TOOL_ROUTING.md`; do not apply `CHATGPT_TOOL_ROUTING.md`.
- If the active runtime is **ChatGPT**, read `CHATGPT_TOOL_ROUTING.md`; do not assume Codex-native browser/shell capabilities.
- Never mix the two runtime hierarchies.
- Load only files needed for the current task.
- Use a branch and PR for non-trivial changes; verify the affected PWA/content behavior.
