# OpenCode Config Directory

This is `~/.config/opencode` — your OpenCode user configuration, not a code project.

## Version Control

- **Jujutsu (jj)** — always use `jj` commands, never git
- This directory is already jj-backed (see `.jj/`)

## Structure

- `opencode.json` — OpenCode permissions and config
- `tui.json` — TUI theme and preferences
- `package.json` — user-level npm dependencies
- `skills/` — custom skill definitions (each subdirectory needs `SKILL.md`)

## Skills

Custom skills live in `skills/<name>/SKILL.md`. Load with:
```
/load-skill <name>
```
