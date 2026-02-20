![Banner](https://raw.githubusercontent.com/ktmcp-cli/pdfgeneratorapi/main/banner.svg)

> "Six months ago, everyone was talking about MCPs. And I was like, screw MCPs. Every MCP would be better as a CLI."
>
> — [Peter Steinberger](https://twitter.com/steipete), Founder of OpenClaw
> [Watch on YouTube (~2:39:00)](https://www.youtube.com/@lexfridman) | [Lex Fridman Podcast #491](https://lexfridman.com/peter-steinberger/)

# PDF Generator API CLI

> **⚠️ Unofficial CLI** - Not officially sponsored or affiliated with PDF Generator API.

Generate PDF documents from templates

## Installation

```bash
npm install -g @ktmcp-cli/pdfgeneratorapi
```

## Quick Start

```bash
# Configure API key
pdfgeneratorapi config set --api-key YOUR_API_KEY

# Show configuration
pdfgeneratorapi config show
```

## Commands

### Config

```bash
pdfgeneratorapi config set --api-key <key>
pdfgeneratorapi config show
```

## JSON Output

All commands support `--json` for structured output:

```bash
pdfgeneratorapi <command> --json | jq
```

## Why CLI > MCP?

No server to run. No protocol overhead. Just install and go.

- **Simpler** — Just a binary you call directly
- **Composable** — Pipe to `jq`, `grep`, `awk`
- **Scriptable** — Works in cron jobs, CI/CD, shell scripts

## License

MIT — Part of the [Kill The MCP](https://killthemcp.com) project.
