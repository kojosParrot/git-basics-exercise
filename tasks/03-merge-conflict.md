# Task 3 — Create and resolve a merge conflict (solo)

Goal: Experience a simple merge conflict and resolve it.

Setup:
We prepared starter/profile.txt with a line: `Favorite color: TBD`

Steps:

1) Make sure your working tree is clean (`git status`).
2) From `main`, create and switch to branch `feature/conflict-a`.
3) Edit starter/profile.txt to say: `Favorite color: Blue` and commit.
4) Switch back to `main`.
5) Create and switch to branch `feature/conflict-b`.
6) Edit starter/profile.txt to say: `Favorite color: Green` and commit.
7) Merge `feature/conflict-a` into `feature/conflict-b`:
   - First, switch to `feature/conflict-b`.
   - Run a merge. You should see a CONFLICT.
8) Open starter/profile.txt, keep one final line that mentions both colors, e.g., `Favorite color: Blue or Green`.
9) Mark conflict as resolved, commit the merge, and push the branch.

Hints:

- Use your editor’s conflict resolution UI if available.
- After resolving, run `git status` to confirm only resolved files remain.
