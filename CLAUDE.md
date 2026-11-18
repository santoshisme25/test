# test

## What this is
A sandbox repo created on 2026-11-18 to verify that Claude Code can
talk to GitHub end-to-end. Not a real product — safe to delete or
reuse as scratch.

## Setup done in this session (applies to all future projects)
- Git identity (global):
  - name: `Santosh`
  - email: `358133231+santoshisme25@users.noreply.github.com` (GitHub no-reply)
  - default branch: `main`
  - credential helper: `osxkeychain`
- GitHub classic PAT (`repo` scope) is stored in macOS Keychain under
  host `github.com`, user `santoshisme25`. Expires in ~90 days; when
  a push suddenly asks for a password, regenerate the token.
- Folder layout:
  - `~/Documents/Personal/Core/Code/` is the parent (not a repo).
  - Each project lives in its own subfolder (this one is `test/`).

## Decisions
- Stay on Apple's system git (2.50.1) — no Homebrew git.
- No code editor installed yet; Claude Code is the primary surface.
  Consider VS Code later if hand-editing becomes common.
- Conceptual Q&A should go to claude.ai chat, not Code, to save tokens.

## Operating checklist (sticky note)
- New project → `"new project <name>: <goal>. set up folder, git, CLAUDE.md, github repo, push."`
- Resume → `"resume <name>. catch up from CLAUDE.md, commits, pull."`
- End session → `"wrap up <name>: update CLAUDE.md, commit, push."`
- Status check → `"status check on <name>"`
- Token-waste flagging is on — I will push back on redundant reads/runs.

## Current state
- One commit (`Initial commit`) on `main`, pushed to
  `https://github.com/santoshisme25/test`.
- This CLAUDE.md is the second commit.

## Open questions / next
- Decide whether `test/` becomes the sandbox for throwaway experiments
  or gets archived once the first real project starts.
