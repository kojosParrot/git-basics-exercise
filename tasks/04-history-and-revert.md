# Task 4 — History and revert

Goal: Inspect commit history and undo one change safely.

Steps:

1) View a compact history graph:
   `git log --oneline --graph --decorate --all`
2) Pick a previous commit you can safely revert (e.g., your change to hello.txt), copy its hash.
3) Create a revert commit:
   `git revert <hash>`
4) Push your branch and confirm the new revert commit appears in your PR.

Hints:

- Revert creates a new commit that undoes the chosen commit — it does not delete history.
- If revert opens an editor, write a short message and save/close.
