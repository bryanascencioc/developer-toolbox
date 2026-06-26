# Merge Conflict Evidence

## Pull Request

Pull Request URL:

```text
https://github.com/bryanascencioc/developer-toolbox/pull/2
```

Pull Request title:

```text
Practice README merge conflict
```

## What caused the conflict

The conflict happened because the same `README.md` Status section was changed in two different branches.

The feature branch changed it to:

```markdown
## Status

Phase 0 active through pull request workflow.
```

The main branch changed it to:

```markdown
## Status

Phase 0 active on main branch.
```

Because both branches changed the same section of the same file, Git could not decide automatically which version to keep.

## GitHub conflict message

```text
This branch has conflicts that must be resolved

Use the web editor or the command line to resolve conflicts before continuing.
```

## How I resolved the conflict

I brought the latest `main` changes into the feature branch, opened `README.md`, removed the conflict markers, and kept a final clean version.

Final accepted version:

```markdown
## Status

Phase 0 active through pull request workflow and merge conflict practice.
```

## Conflict resolution commit

```text
da21029 Resolve README status merge conflict
```

## Merge commit

```text
9f68a76 Merge pull request #2 from bryanascencioc/feature/readme-status-conflict
```

## Final repository status

```text
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
```

## What I learned

A merge conflict happens when two branches change the same part of the same file.

To resolve it, I need to:

1. Understand both versions.
2. Remove the conflict markers.
3. Keep the correct final version.
4. Stage the resolved file.
5. Commit the resolution.
6. Push the branch.
7. Confirm the pull request is ready to merge.

## Process lesson

In real engineering teams, I should wait for reviewer approval before merging a pull request.
