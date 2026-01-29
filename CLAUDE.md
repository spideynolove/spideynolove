# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Type

This is a **personal GitHub profile repository**, not a traditional software project. It contains no source code or build system—only profile documentation and assets.

## Repository Structure

```
spideynolove/
├── README.md          # Main GitHub profile (publicly displayed)
├── README-draft.md    # Draft version for profile updates
├── resources/         # GIF assets used in profile
│   ├── ohara.gif
│   ├── ohara2.gif
│   └── ohara3.gif
└── .github/
    └── workflows/
        └── waka-readme.yml    # Empty workflow file
```

## Working with This Repository

**Primary Tasks:** Updates to README.md for profile changes (skills, projects, badges, links)

**No Build/Test/Lint Commands:** This repository contains no code to build, test, or lint.

**Profile Updates:**
1. Draft changes in README-draft.md first
2. Preview locally if needed
3. Update README.md when ready
4. Commit with descriptive message

## Profile Content Notes

- Uses shields.io badges extensively for visual elements
- References local GIF assets in `resources/` directory
- Integrates GitHub stats via external services (github-readme-stats, github-readme-streak-stats)
- Shows technology focus: Python (primary), JavaScript, web scraping (Scrapy, Playwright), ML/ML (PyTorch, NumPy, Pandas), DevOps (Docker, Kubernetes, Terraform)

## Current Focus

The profile highlights "Stock Advisor" as the main current project—an AI-powered investment tool.
