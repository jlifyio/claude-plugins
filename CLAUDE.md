# claude-plugins — public marketplace `jlifyio`

Registry only: `.claude-plugin/marketplace.json` (1 plugin: wyx) + README §Plugins table. No code.
- `description`/`keywords`/`license` MUST mirror the plugin's `.claude-plugin/plugin.json`; no `version` field here — plugin.json is the version authority. release-kit pre-flight 9c reports drift; fix it here in a follow-up commit.
- README §Plugins row changes in the same commit as marketplace.json.
- Check: `claude plugin validate .` (marketplace manifest — passes today).
- Consumers: `/plugin marketplace add jlifyio/claude-plugins` → `/plugin install wyx@jlifyio` (canonical strings; wyx-example's README has stale ones).
- Private siblings: claude-plugins-private (`jlifyio-private`).
