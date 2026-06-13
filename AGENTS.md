# Repository Guidelines

## Project Structure & Module Organization

This repository is a catalog of Paperclip agent companies. Each top-level company directory uses a lowercase, hyphenated slug such as `agentsys-engineering/` or `trail-of-bits-security/`.

Expected company layout:

```text
<company-slug>/
  COMPANY.md
  README.md
  LICENSE
  agents/<agent-slug>/AGENTS.md
  skills/<skill-slug>/SKILL.md
  teams/<team-slug>/TEAM.md
  images/
```

`COMPANY.md` contains Agent Companies metadata and must declare `schema: agentcompanies/v1`. Agent instructions live in `agents/**/AGENTS.md`; reusable workflows live in `skills/**/SKILL.md`; org charts and supporting media belong in `images/`.

## Build, Test, and Development Commands

There is no root build system. Validate packages with the Paperclip CLI:

```bash
npx paperclipai company import --from ./agentsys-engineering --dry-run
npx companies.sh add paperclipai/companies/agentsys-engineering
```

Use `--dry-run` before submitting changes to a company. Use the `companies.sh` command when checking the published import path documented in the root `README.md`.

## Coding Style & Naming Conventions

Use Markdown for all company, agent, skill, team, and contributor documentation. Keep prose direct and task-oriented. Prefer lowercase, hyphenated slugs for directories: `skills/code-review/SKILL.md`, `agents/staff-engineer/AGENTS.md`.

Keep `README.md` focused on what the company is and how to import it. Keep `AGENTS.md` focused on contributor or agent operating instructions. Do not duplicate long catalog listings between files.

## Testing Guidelines

For any company change, run an import dry-run against the affected directory. For structural edits, spot-check required files:

```bash
find ./agentsys-engineering -name 'COMPANY.md' -o -name 'AGENTS.md' -o -name 'SKILL.md'
```

When adding images, verify relative Markdown links render from the company README.

## Commit & Pull Request Guidelines

Recent commits use short, imperative summaries such as `Replace pnpm with npx for paperclipai CLI commands` and `Enforce CEO as root agent across all 16 companies`. Follow that style and keep one logical change per commit.

Pull requests should describe the company or package changed, summarize validation performed, and link related upstream sources or issues. Keep PRs scoped to one company where practical, especially when importing or refreshing upstream skills.
