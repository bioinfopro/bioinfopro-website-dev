# Jekyll & Claude Code Guidelines

## Directory Architecture
- `src/`: Public website source code (layouts, includes, posts, pages, index.md).
- `src/assets/css`: Public website CSS style guide 
- `agents/`: Private AI agent prompts and instructions (outside web root).
- `skills/`: Private AI agent skills and instructions (outside web root).

## Security Rules
- All new public pages must be created inside `src/pages/` or `src/`.
- Never put API keys, internal credentials, or files from `agents/` into `src/`.

## Commands
- Run local server: `bundle exec jekyll serve`
- Build site: `bundle exec jekyll build`