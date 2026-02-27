# claude-plugins

Claude Code plugin marketplace by [jlifyio](https://github.com/jlifyio).

## Plugins

| Plugin | Description | Category |
|--------|-------------|----------|
| [wyx](https://github.com/jlifyio/wyx) | Architecture guardrails — automatically injects module boundaries into Claude's context on every write | Development |

## Installation

Add this marketplace to your Claude Code configuration:

```bash
claude plugin add jlifyio/claude-plugins
```

Then install individual plugins:

```bash
claude plugin install wyx
```

## Structure

```
.claude-plugin/
  marketplace.json   # Plugin registry
```

## License

MIT
