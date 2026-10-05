# cc-plugins

Claude Code plugins by Dave Kiss, in one marketplace.

```
/plugin marketplace add davekiss/cc-plugins
```

Then install any of them:

| Plugin | Install | What it does |
| --- | --- | --- |
| [md](https://github.com/davekiss/md) | `/plugin install md@davekiss` | Read, write and review markdown with Claude in a pane inside Claude Code. |
| [env](https://github.com/davekiss/env) | `/plugin install env@davekiss` | Edit .env files in a pane. Claude manages keys and asks you for values without ever seeing them. |
| [shot](https://github.com/davekiss/shot) | `/plugin install shot@davekiss` | Headless macOS screenshots for agents: capture, mark up, redact, record and find screenshots without taking focus. |

From a terminal: `claude plugin marketplace add davekiss/cc-plugins`, then `claude plugin install <name>@davekiss`.

## Adding a plugin

Each plugin lives in its own repo. Add an entry to `.claude-plugin/marketplace.json` pointing at it (`github` for a plugin at the repo root, `git-subdir` for one in a folder), run `claude plugin validate .`, and push.
