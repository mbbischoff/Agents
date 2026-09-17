# personal agent instructions

`AGENTS.md` is the source of truth for mb’s personal agent instructions. this repository is private.

## local setup

the repository lives at `~/Code/Personal/Agents`.

- codex: `~/.codex/AGENTS.md` links to this repository’s `AGENTS.md`.
- claude code: `~/.claude/CLAUDE.md` links to this repository’s `AGENTS.md`.
- `CLAUDE.md` inside this repository is also a relative symlink to `AGENTS.md`.

edit `AGENTS.md` here; both global links read the same file. commit and push changes to back them up on github. links do not automatically commit or synchronize changes between machines.

on another mac, clone the private repository to the same location and create the two global symlinks after checking for existing instruction files. preserve existing files before replacing them. start a new session to load updated instructions.

## documentation

- [codex global instructions](https://learn.chatgpt.com/docs/agent-configuration/agents-md)
- [claude code user instructions](https://code.claude.com/docs/en/memory)
