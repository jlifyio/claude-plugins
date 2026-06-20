# claude-plugins

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Claude Code Marketplace](https://img.shields.io/badge/Claude_Code-Marketplace-orange)](https://claude.com/claude-code)

Claude Code plugin marketplace by [jlifyio](https://github.com/jlifyio).

## Plugins

| Plugin | Description | Category |
|--------|-------------|----------|
| [wyx](https://github.com/jlifyio/wyx) | Architecture guardrails for Claude Code — automatically injects module boundaries into Claude's context on every write | Development |

## Install

Inside Claude Code, add the marketplace and install a plugin:

```
/plugin marketplace add jlifyio/claude-plugins
/plugin install wyx@jlifyio
```

Or from your shell:

```bash
claude plugin marketplace add jlifyio/claude-plugins
claude plugin install wyx@jlifyio
```

## Try it

New to wyx? Clone [wyx-example](https://github.com/jlifyio/wyx-example) — a small e-commerce project with pre-written specs and intentional drift to discover in about 2 minutes.

## Structure

```
.claude-plugin/
  marketplace.json   # Plugin registry
.gitignore
LICENSE              # MIT
README.md
```

## License

[MIT](LICENSE)
