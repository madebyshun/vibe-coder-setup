# The Vibe Coder Setup — by @madeby.shun

Thanks for commenting "SKILL" 🙌
This is the exact setup I use to ship products with Claude Code — no dev team, no handoff.

## What's inside
| File | What it does |
|---|---|
| `CLAUDE.md` | Your project brain: brand, stack, rules. Claude reads it every session. |
| `skills/ui-polish/` | Makes AI-built UI stop looking AI-built. |
| `skills/landing-page/` | Plan → build a landing page in your brand. |
| `skills/ship-check/` | Pre-launch review: bugs, mobile, accessibility, SEO. |

## Setup (5 minutes)
1. Install Claude Code → https://claude.com/claude-code
2. Copy `CLAUDE.md` into the root of your project. Fill in the `[brackets]`.
3. Copy the `skills/` folders into `~/.claude/skills/` (all projects) or `.claude/skills/` (this project only).
4. Open Claude Code in your project and just ask, e.g. *"build a landing page for my app"* — the matching skill loads automatically. Or call it directly: `/landing-page`.

## My 5 rules for vibe coding
1. **Plan first.** Press `Shift+Tab` for plan mode. Approve the plan like a design brief before any code.
2. **One feature per session.** Small asks = fewer bugs.
3. **Show, don't describe.** Paste a screenshot of what you want. It reads images.
4. **Commit often.** Ask Claude to `git commit` after every working step so you can always go back.
5. **Review everything.** Run `/ship-check` before you launch. AI is fast, not perfect.

## Useful connectors (MCP)
- **GitHub** — commits, PRs, issues
- **Vercel** — deploy and read logs
- **Figma** — read your designs straight into code
- **Browser** — Claude opens your app and checks it visually

Built something with this? Tag @madeby.shun — I reshare the good ones.
