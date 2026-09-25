# Claude Code Learning Lab

A safe place where I practice Claude Code, Git, and GitHub, and publish my junior projects.

## Author

Ambroise Abanda

## Claude Code settings

`.claude/settings.json` holds project permissions that Claude Code enforces:

- `ask`: Claude must get my approval before any `git push`.
- `deny`: Claude cannot read `.env` files, where secrets would live.
