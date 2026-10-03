# 🧸 Mio's Mods

Cozy little mods for Claude Code.

| Mod | What it does |
| --- | --- |
| [🌷 Garden Claude](https://github.com/milkoya/garden-claude) | A pixel-art Claude tends a flower garden above your prompt while you work |
| [📊 Usage Tracking](https://github.com/milkoya/usage-tracking) | A side panel with your Claude Code cost and token usage: daily and weekly charts from your local logs |
| [🧹 Tidy Edits](https://github.com/milkoya/tidy-edits) | Short cards for every file Claude edits instead of long line diffs, with each file's diff a click away |

## Install

Add the marketplace once:

```sh
claude plugin marketplace add milkoya/mods
```

Then install the mods you want:

```sh
claude plugin install garden-claude@milkoya
claude plugin install usage-tracking@milkoya
claude plugin install tidy-edits@milkoya
```

Start a new Claude Code session to load them.

These mods are built on Claude Code's **function hooks**, an early-access feature that's still rolling out. If your Claude Code doesn't load them yet, it will once the feature reaches you.

## License

MIT © Mio
