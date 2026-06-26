# PowerShell Basics

PowerShell is a command-line shell used to run commands, automate tasks, manage files and folders, run scripts, and work with development projects on Windows.

## Why PowerShell matters

PowerShell matters because many real Windows development environments use it to navigate projects, run Git commands, execute scripts, inspect folders, and automate tasks.

## Basic commands

| Task                   | Command                     |
| ---------------------- | --------------------------- |
| Show current folder    | `pwd`                       |
| List files and folders | `ls`                        |
| Move into a folder     | `cd folder-name`            |
| Move up one folder     | `cd ..`                     |
| Create a folder        | `mkdir folder-name`         |
| Create a file          | `New-Item file-name.txt`    |
| Read a file            | `Get-Content file-name.txt` |
| Remove a file          | `Remove-Item file-name.txt` |

## Example workflow

```powershell
pwd
ls
cd docs
ls
cd ..
```

## What I learned

I learned that PowerShell lets me interact with my computer using commands instead of clicking through folders manually.
