# Jekyll & Claude Code Guidelines

## Directory Architecture
- `src/`: Public website source code (layouts, includes, posts, pages, index.md).
- `src/assets/css`: Public website CSS style guide 
- `agents/`: Private AI agent prompts and instructions (outside web root).
- `skills/`: Private AI agent skills and instructions (outside web root).

## Security Rules
- All new public pages must be created inside `src/pages/` or `src/`.
- Never put API keys, internal credentials, or files from `agents/` into `src/`.

## Git Rules
- No agent (main thread or any subagent, current or future) may run `git commit`, `git push`, or any command that publishes to a remote or rewrites shared history — in this or any repo it works in. This is enforced technically via `permissions.deny` in `.claude/settings.json` (`Bash(git commit*)`, `Bash(git push*)`), not just as a prose rule.
- Leave changes staged/unstaged in the working tree and report what changed. Committing and pushing is always the user's explicit, in-the-moment action — never assume a prior approval carries forward to a later commit/push.
- If a task genuinely can't be finished without a commit or push, stop and tell the user what's blocked and why, rather than working around the restriction.

## Commands
- Run local server: `bundle exec jekyll serve`
- Build site: `bundle exec jekyll build`