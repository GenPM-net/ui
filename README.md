# @core/ui

[![genpm](https://api.genpm.net/v1/badge/@core/ui.svg)](https://genpm.net/p/@core/ui) ![license](https://img.shields.io/badge/license-MIT-blue)

> Accessible base UI for React on native elements: fields, buttons, table, tabs, dialog, toasts and WCAG AA light/dark tokens

A [GenPM](https://genpm.net) module: **source code + AI rules + MCP config**, injected into your project instead of hidden in `node_modules`. The code lands in `src/lib/ui`, pinned to a verified commit, and you own it.

## Install

```bash
genpm add @core/ui
```

No genpm yet? `curl -fsSL https://genpm.net/install.sh | sh` (macOS/Linux), `irm https://genpm.net/install.ps1 | iex` (Windows), or one-off with `npx @genpm-net/cli add @core/ui`.

Or let your AI agent do it: run `genpm mcp setup` once, then ask *"add @core/ui with genpm"* in Claude Code, Cursor, VS Code, Windsurf, Codex or Gemini CLI. It shows you a dry-run plan before writing anything.

## What it does

Small accessible component set for React built on native elements (no UI library): `Button`, `TextField`,
`TextareaField`, `SelectField`, `Checkbox`, `Field` (label + help + error wiring), `DataTable` (with `aria-sort`),
`Pagination`, `Tabs` (WAI-ARIA, arrow keys), `Dialog` (native `<dialog>`), `Alert`, `Badge`, `Card`, `Toasts`,
`Spinner`, `Skeleton`. Styling lives in `ui.css` as CSS variables (light/dark, WCAG AA contrast) and `ui-*` classes.
Used by @core/admin, @core/blocks and the kits.

## At a glance

- **npm dependencies** (proposed, never installed without asking): `react`
- **AI rules**: [`AGENTS.md`](AGENTS.md), loaded by your agent only when it works in `src/lib/ui`

## Security

GenPM installs a 40-character commit SHA (never a branch), verifies an Ed25519-signed manifest, never runs install scripts and scans AI rules for prompt injection. Details: [genpm.net/docs/security](https://genpm.net/docs/security).

## License

MIT — see [LICENSE](LICENSE). Browse the full catalog at [genpm.net](https://genpm.net).
