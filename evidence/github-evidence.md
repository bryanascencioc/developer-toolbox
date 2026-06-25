# GitHub Evidence

## 1. GitHub repository created

Repository URL:

```text
https://github.com/bryanascencioc/developer-toolbox.git
```

## 2. Branch renamed to main

Command used:

```powershell
git branch -M main
```

Output:

```text
No output shown. Branch was renamed successfully.
```

Verification command:

```powershell
git status
```

Output:

```text
On branch main
nothing to commit, working tree clean
```

## 3. Remote added

Command used:

```powershell
git remote add origin https://github.com/bryanascencioc/developer-toolbox.git
```

Output:

```text
No output shown. Remote was added successfully.
```

Verification command:

```powershell
git remote -v
```

Output:

```text
origin  https://github.com/bryanascencioc/developer-toolbox.git (fetch)
origin  https://github.com/bryanascencioc/developer-toolbox.git (push)
```

## 4. First push to GitHub

Command used:

```powershell
git push -u origin main
```

Output:

```text
Enumerating objects: 23, done.
Counting objects: 100% (23/23), done.
Delta compression using up to 4 threads
Compressing objects: 100% (19/19), done.
Writing objects: 100% (23/23), 5.66 KiB | 482.00 KiB/s, done.
Total 23 (delta 4), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (4/4), done.
To https://github.com/bryanascencioc/developer-toolbox.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
```

## 5. GitHub repository check

I confirmed on GitHub that the repository contains:

```text
README.md
.gitignore
docs/
evidence/
scripts/
```

## 6. Concepts

### Local repository

A local repository is the Git-tracked project on my computer.

### Remote repository

A remote repository is the online version of the repository hosted on GitHub.

### Origin

origin is the common default name used for the remote repository.

### Push

git push sends local commits to the remote repository.

### Upstream branch

An upstream branch connects a local branch to a remote branch so Git knows where to push and pull by default.

### Main branch

main is the primary branch of the repository.
