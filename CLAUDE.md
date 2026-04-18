# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

GitHub profile repository — a single `README.md` displayed on Francesco's GitHub profile page. No build system, no tests, no dependencies.

## Linting

```bash
npx markdownlint-cli README.md
```

Lint rules defined in `.markdownlint.json`: inline HTML (`MD033`) and line length (`MD013`) are disabled.

## README structure

1. Hook line + intro bullets (role, location)
2. **Projects** — `github-readme-stats` repo pin cards for: SplitDuo, PodCats, digital-signature-poc, markdown-to-pdf
3. **Skills** — split into: Primary Stack / Also worked with / DevOps & Infrastructure / Tools / OS — using `shields.io` badges
4. **Stats** — GitHub stats card, top-langs card, streak card via `github-readme-stats.vercel.app` and `streak-stats.demolab.com`
5. **Connect** — LinkedIn, website, resume, email as badge links

## Repo pin card format

```markdown
[![Label](https://github-readme-stats.vercel.app/api/pin/?username=c4mbr0nn3&repo=<repo>&title_color=0891b2&text_color=ffffff&icon_color=0891b2&bg_color=1c1917&hide_border=true)](https://github.com/c4mbr0nn3/<repo>)
```

## Badge format

Shields.io badges follow this pattern:

```markdown
![Label](https://img.shields.io/badge/<label>-<color>?style=for-the-badge&logo=<logo-slug>&logoColor=<color>)
```

Logo slugs come from [Simple Icons](https://simpleicons.org/). Colors are hex without `#` or named colors.
