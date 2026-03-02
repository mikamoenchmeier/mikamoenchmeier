# CLAUDE.md — AI Assistant Guide for mikamoenchmeier

## Repository Overview

This is a **GitHub Profile Repository** — a special GitHub repository whose `README.md` is automatically displayed as the public-facing profile page for the GitHub user [@mikamoenchmeier](https://github.com/mikamoenchmeier). It contains no application code, build system, or dependencies.

**Repository type:** GitHub profile (documentation only)
**Primary file:** `README.md`
**Purpose:** Personal branding, portfolio introduction, and social links

---

## Repository Structure

```
mikamoenchmeier/
├── README.md     # GitHub profile page (the only tracked file)
└── CLAUDE.md     # This file — AI assistant guide
```

No subdirectories, no source code, no configuration files, no CI/CD pipelines.

---

## Developer Profile

**Name:** Mika Moenchmeier
**Language:** German (native), English

### Tech Stack (as declared in README)

| Category      | Technologies                                      |
|---------------|---------------------------------------------------|
| Languages     | HTML5, CSS3, JavaScript, Java, Shell Script, Swift |
| Tools/Infra   | Docker, Linux, Cloudflare, Blender                |
| Currently learning | HTML, CSS, JavaScript, Java                  |

### Active Projects (as declared in README)

- Personal website
- Minecraft server website
- Minecraft server development

---

## Editing the README

The `README.md` is a standard GitHub-flavored Markdown file. It uses:

- **Shield.io badges** for tech stack and social links (pattern: `https://img.shields.io/badge/...`)
- **Third-party widgets** for dynamic GitHub stats:
  - `github-readme-stats.vercel.app` — contribution stats and top languages
  - `github-readme-streak-stats.herokuapp.com` — streak stats
  - `github-profile-trophy.vercel.app` — trophy display
  - `quotes-github-readme.vercel.app` — random dev quote
  - `github-contributor-stats.vercel.app` — top contributed repos
  - `visitcount.itsvg.in` — profile visit counter
  - `gtce.itsvg.in` — latest tweet card
- **Ko-fi** donation link
- Generated with [GPRM](https://gprm.itsvg.in)

### When updating the README

1. Keep the badge style consistent (`style=flat` for tech stack, `style=for-the-badge` for donation).
2. All social links follow the pattern `https://<platform>.com/mikamoenchmeier` (or the platform-specific URL format).
3. The color theme across all stats widgets is `radical` with `hide_border=true`.
4. Preserve the `<!-- Proudly created with GPRM ... -->` comment at the bottom.
5. Do not remove or rearrange existing sections unless explicitly asked.

---

## Git Workflow

### Branches

- `main` — primary branch on the remote (`origin/main`)
- `master` — local default branch (legacy name)
- Feature branches follow the pattern: `claude/<description>-<id>` (e.g., `claude/add-claude-documentation-QZ4x2`)

### Commit conventions

This repo has no enforced commit message format. Commits to date have used plain imperative messages:

```
Create README.md
Update README.md
```

For AI-assisted changes, prefer descriptive messages:

```
Add CLAUDE.md with codebase documentation
Update README: add new social link for <platform>
```

### Push instructions

Always push with the upstream flag:

```bash
git push -u origin <branch-name>
```

Branch names for AI-generated work must start with `claude/` and end with the session ID suffix.

---

## No Build, Test, or Lint Steps

This repository has **no build system, no test suite, and no linter**. There is nothing to install or run. All changes are to Markdown files only.

---

## Conventions for AI Assistants

- **Minimal changes only.** This is a personal branding page — do not restructure it unless explicitly asked.
- **Preserve existing badge style and theme.** All stats widgets use the `radical` theme; keep this consistent if adding new widgets.
- **Do not add content about projects or skills** unless the user confirms they want to update their profile with new information.
- **Do not create additional files** (source code, configs, scripts) unless explicitly requested. This is intentionally a documentation-only repository.
- **Social links belong in the Socials section** using the existing shield.io badge pattern.
- **New tech stack items belong in the Tech Stack section** using `style=flat` badges from shield.io.
