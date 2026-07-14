# Installation

This template is prepared for the GitHub account `mrnko`.

## Repository structure

```text
mrnko/
├── .github/
│   └── workflows/
│       └── snake.yml
├── assets/
│   ├── profile-terminal-dark.svg
│   └── profile-terminal-light.svg
└── README.md
```

## How to publish

1. Open the special profile repository: `https://github.com/mrnko/mrnko`.
2. Replace its `README.md` with the included version.
3. Upload the `.github` and `assets` directories without changing their paths.
4. Commit the files to the `main` branch.
5. Open the repository's **Actions** tab.
6. Select **Generate Contribution Snake**.
7. Click **Run workflow**.
8. After the workflow finishes, refresh `https://github.com/mrnko`.

The workflow also runs automatically every day and after a push to `main`.

## What to edit first

- Verify the Freecora stack in the Featured Projects table.
- Add or remove projects from Featured Projects.
- Rewrite the About Me bullets as your positioning evolves.
- Remove stats widgets you do not like.
- Edit both SVG terminal cards when the displayed information changes.

## Common issue

The contribution snake will be empty or broken until the workflow successfully creates the `output` branch for the first time.
