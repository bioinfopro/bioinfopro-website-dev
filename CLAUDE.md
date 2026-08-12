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
- `git commit`, `git push`, and any command that publishes to a remote or rewrites shared history require the user's explicit, in-the-moment approval — never assume a prior approval carries forward to a later commit/push. This is enforced technically via `permissions.ask` in `.claude/settings.json` (`Bash(git commit*)`, `Bash(git push*)`): every such command, from the main thread or any subagent, pauses for a permission prompt the user must approve before it runs. (Claude Code's permission system can't scope a rule to "subagents only" — an `ask` rule applies project-wide to whoever issues the command, which is why the main thread is gated too.)
- Subagents (`.claude/agents/*.md`) are additionally instructed to never run these commands themselves at all, even with the prompt available — committing and pushing is the main thread/user's call, not something a subagent should reach for even to "finish" a task.
- If a task genuinely can't be finished without a commit or push, say so and let the user decide, rather than working around the restriction.

## Commands
- Run local server: `bundle exec jekyll serve`
- Build site: `bundle exec jekyll build`