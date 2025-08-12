# Contributing Guide

Welcome! This guide expands the quick start in `README.md`.

## 1. Fork & Clone

1. Click "Fork" to create your copy.
2. Clone your fork:
   ```bash
   git clone https://github.com/<your-username>/your-first-contribution-.git
   cd your-first-contribution-
   ```
3. Add the original repo as an "upstream" remote (optional for now):
   ```bash
   git remote add upstream https://github.com/Code4Camp/your-first-contribution-.git
   ```

## 2. Create a Branch

Use a descriptive branch name:

```
add-your-name
fix-typo-readme
feat-new-task-template
```

```
git checkout -b add-your-name
```

## 3. Choose a Starter Task

Open `tasks/README.md`. Pick ONE unclaimed task. If it asks you to add your name somewhere, do that edit.

## 4. Make Your Change

Edit the file(s). Keep changes minimal and focused.

## 5. Commit

Stage only relevant files:

```
git add CONTRIBUTORS.md
```

Write a concise commit message:

```
git commit -m "docs: add Jane Doe to contributors"
```

## 6. Push

```
git push -u origin add-your-name
```

## 7. Open a Pull Request

GitHub will show a compare link. Fill in the PR template sections. Keep the checklist items that apply.

## 8. Review Cycle

A maintainer (or helpful previous contributor) may request tweaks. Push new commits to the same branch. They appear automatically in the PR.

## 9. Merge & Celebrate

Once approved, a maintainer merges. Your GitHub profile now shows your first public contribution 🎉.

---

## Style & Conventions

- Keep PRs atomic: one logical change.
- Use lowercase, hyphenated branch names.
- Avoid trailing whitespace.
- Prefer inclusive, encouraging wording.

## Commit Types (lightweight)

`docs`, `chore`, `feat`, `fix`, `refactor`.

## Adding a New Beginner Task

1. Open an issue proposing it (so we avoid duplicates).
2. If accepted, add it under the correct section in `tasks/README.md` with: description, difficulty (1–5), and status `OPEN`.

## Helping Others

After your first merge:

- Comment with encouragement.
- Suggest improvements politely.
- Never mock mistakes—everyone starts somewhere.

## Getting Unstuck

Open an issue using the Question template OR turn your PR into a draft with a note like: "Need help understanding the failing check." Someone will guide you.

## Keeping Your Fork Updated (optional advanced)

```
git fetch upstream
git checkout main
git merge upstream/main
# or: git rebase upstream/main
```

Then re-create branches from updated `main`.

## Code of Conduct

All participation is covered by `CODE_OF_CONDUCT.md`.

Happy contributing! 🌟
