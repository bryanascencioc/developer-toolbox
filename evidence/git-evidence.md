# Git Evidence

## 1. Git version check

Command used:

```powershell
git --version
```

Output:

```text
git version 2.52.0.windows.1
```

## 2. Repository initialization

Command used:

```powershell
git init
```

Output:

```text
Initialized empty Git repository in C:/Users/bryan/OneDrive/Documentos/Dev/developer-toolbox/.git/
```

## 3. Git status before staging

Command used:

```powershell
git status
```

Output:

```text
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        README.md
        docs/
        evidence/
        scripts/

nothing added to commit but untracked files present (use "git add" to track)
```

## 4. Git diff before staging

Command used:

```powershell
git diff
```

Output:

```text
No output was shown. This is normal because the files were new and untracked.
```

## 5. Files staged

Command used:

```powershell
git add .
git status
```

Output:

```text
warning: in the working copy of 'scripts/bash/hello-toolbox.sh', LF will be replaced by CRLF the next time Git touches it

On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   .gitignore
        new file:   README.md
        new file:   docs/terminal/bash-basics.md
        new file:   docs/terminal/powershell-basics.md
        new file:   evidence/bash-evidence.md
        new file:   evidence/terminal-evidence.md
        new file:   scripts/bash/hello-toolbox.sh
        new file:   scripts/powershell/hello-toolbox.ps1
```

## 6. First commit

Command used:

```powershell
git commit -m "add initial developer toolbox structure"
```

Output:

```text
[master (root-commit) 5f487a1] add initial developer toolbox structure
 8 files changed, 502 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 README.md
 create mode 100644 docs/terminal/bash-basics.md
 create mode 100644 docs/terminal/powershell-basics.md
 create mode 100644 evidence/bash-evidence.md
 create mode 100644 evidence/terminal-evidence.md
 create mode 100644 scripts/bash/hello-toolbox.sh
 create mode 100644 scripts/powershell/hello-toolbox.ps1
```

## 7. Commit message correction

Command used:

```powershell
git commit --amend -m "Add initial developer toolbox structure"
```

Output:

```text
[master 31f4fdb] Add initial developer toolbox structure
 Date: Thu Jun 25 12:39:52 2026 +0200
 8 files changed, 502 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 README.md
 create mode 100644 docs/terminal/bash-basics.md
 create mode 100644 docs/terminal/powershell-basics.md
 create mode 100644 evidence/bash-evidence.md
 create mode 100644 evidence/terminal-evidence.md
 create mode 100644 scripts/bash/hello-toolbox.sh
 create mode 100644 scripts/powershell/hello-toolbox.ps1
```

## 8. Git log

Command used:

```powershell
git log --oneline
```

Output captured during the evidence review:

```text
91f856c (HEAD -> master) Add Git basics evidence
31f4fdb Add initial developer toolbox structure
```

## 9. Concepts

### Git

Git is a version control system that tracks changes in a project over time.

### Repository

A repository is a project folder tracked by Git.

### Working tree

The working tree is the current state of the files in my project folder.

### Staging area

The staging area is where I prepare selected changes before creating a commit.

### Commit

A commit is a saved snapshot of changes in Git history.

### git status

`git status` shows the current state of the repository, including modified, staged, and untracked files.

### git add

`git add` moves changes into the staging area.

### git commit

`git commit` saves staged changes into the Git history.

### git log

`git log` shows the commit history.

### git diff

`git diff` shows file changes that have not yet been committed. In this task, it showed no output because the files were new and untracked.

### .gitignore

`.gitignore` tells Git which files or folders should not be tracked.
