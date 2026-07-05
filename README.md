# ui-ux-pro-max

Design intelligence skill for Claude Code — 67 styles, 96 palettes, 57 font pairings, 99 UX guidelines, 25 chart types, 13 stacks (React, Next.js, Vue, Svelte, SwiftUI, React Native, Flutter, Tailwind, shadcn/ui…).

Claude Code invokes this skill automatically on UI/UX tasks: `plan`, `build`, `design`, `implement`, `review`, `fix`, `improve`, `optimize`, `refactor`. See [`SKILL.md`](SKILL.md) for the full trigger list and rule categories.

## Install (one command)

```bash
git clone https://github.com/<ton-user>/ui-ux-pro-max ~/.claude/skills/ui-ux-pro-max
```

Then restart Claude Code (or open a new session). The skill will appear as `ui-ux-pro-max` and auto-load when a UI/UX task is detected.

### Update

```bash
git -C ~/.claude/skills/ui-ux-pro-max pull
```

### Uninstall

```bash
rm -rf ~/.claude/skills/ui-ux-pro-max
```

## What's inside

- `SKILL.md` — trigger metadata + rule catalog Claude reads first
- `data/` — CSVs: styles, palettes, typography, UX guidelines, charts, icons, per-stack recipes
- `scripts/` — search / design-system helpers Claude can execute

## License

MIT — do whatever, attribution appreciated.
