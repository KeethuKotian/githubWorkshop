# Git and GitHub Workshop Handbook

A practical, 2-hour workshop for beginners. Three parts, 40 minutes each.

## Reading order

Read in this order while preparing, then teach directly from the files:

1. [01-git-fundamentals.md](01-git-fundamentals.md)
2. [02-github-and-remote-operations.md](02-github-and-remote-operations.md)
3. [03-branching-merging-and-collaboration.md](03-branching-merging-and-collaboration.md)

## 120-minute schedule

| Part | Topic | Time | Core (must teach) | Optional |
|---|---|---:|---|---|
| 1 | Git fundamentals and local operations | 40 min | init, status, add, commit, diff, log, restore, config, detached HEAD | `revert`, `reset --hard` (talk only) |
| 2 | GitHub and remote operations | 40 min | remote, push, **fetch vs pull**, `branch -r/-a`, incoming commits | `git remote show origin`, `pull.rebase` |
| 3 | Branching, merging, conflicts | 40 min | branch, switch, merge, **conflict demo**, `merge --abort` | Forks and pull requests |
| | **Total** | **120 min** | | |

Each file has its own minute-by-minute table near the end.

## Section tags used in every file

| Tag | Meaning |
|---|---|
| `[MUST_TEACH]` | Essential content |
| `[LIVE_DEMO]` | Commands you run in front of students |
| `[STUDENT_PRACTICE]` | Tasks students do themselves |
| `[OPTIONAL]` | Only if time remains |

## Before the workshop

- Git installed on every machine (`git --version`).
- GitHub account and working authentication (personal access token, GitHub CLI, or SSH key) for Part 2. Test this **in advance**.
- Practise each exercise once yourself. Sample outputs in the files came from real runs with Git 2.43, but your versions and hashes will differ.
- Default branch name: the files use `main`. If a machine shows `master`, substitute it.

## Viewing the files and Mermaid diagrams

- **GitHub:** push the folder to a repository and open the files in the browser. Mermaid diagrams render automatically, and the `<details>` answer blocks collapse.
- **VS Code:** open a file and press `Ctrl+Shift+V` (preview). Mermaid needs an extension such as "Markdown Preview Mermaid Support".
- **Elsewhere:** each diagram is plain text inside a ```` ```mermaid ```` block. Paste it into [mermaid.live](https://mermaid.live) to view or edit it.

There are no image files. All visuals are editable text diagrams, so no `images/` folder was needed.
