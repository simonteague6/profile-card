# Profile Card

A simple profile card built with HTML and CSS. This project is designed to help beginners explore how git tracks changes over time.

Each commit on `main` adds one small piece. The branches show how real teams work — fix a bug on a branch, merge it back. Add a feature on a branch, merge it back.

## Branches

| Branch | What it does |
|---|---|
| `main` | The profile card, built up commit by commit |
| `bugfix/typo-in-bio` | Fixes a typo ("develpoer" → "developer"), then merged into main |
| `feature/add-paragraph` | Adds a learning goals paragraph, then merged into main |

## How to use

Open `index.html` in your browser. Use Zed's git graph to see how the commits and branches connect.

```bash
git log --oneline --graph --all   # see the full history
```
