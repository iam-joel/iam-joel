# AGENTS.md

Guidance for coding agents (Claude Code reads this via the CLAUDE.md symlink) working in this repository.

## What this repo is

`iam-joel/iam-joel` is a GitHub profile README repo: because the repo name
matches the owner's username, GitHub renders `README.md` on
`github.com/iam-joel`. There is no application code, no build tooling, and
no CI — just `README.md` and `.github/CODEOWNERS`.

## Commands

None. There is nothing to install, build, lint, or test.

## Conventions

- `README.md` is profile-facing content (bio, badges, tech stack, stats
  widgets) rendered on the GitHub profile page — not developer docs.
- Keep edits to `README.md` limited to content changes (bio text, links,
  badges, stack list); don't add project scaffolding.

## What not to touch

- Do not add package.json, CI workflows, or other project tooling — this
  repo is intentionally content-only.
- `.github/CODEOWNERS` sets review ownership; leave it as-is unless asked.
