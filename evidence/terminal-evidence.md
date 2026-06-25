# Terminal Evidence

## Approved project root

```powershell
C:\Users\bryan\OneDrive\Documentos\Dev\developer-toolbox
```

This is the official local project root for Phase 0 Module 0–1.

---

## 1. Current working directory

Command used:

```powershell
pwd
```

Output:

```text
Path
----
C:\Users\bryan\OneDrive\Documentos\Dev\developer-toolbox
```

Explanation:

The `pwd` command shows the current folder where the terminal is located. In this case, the terminal is located inside the approved project root.

---

## 2. Project root structure check

Command used:

```powershell
ls
```

Output:

```text
Directory: C:\Users\bryan\OneDrive\Documentos\Dev\developer-toolbox

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
dar--l         6/19/2026   1:42 PM                docs
dar--l         6/19/2026   1:48 PM                evidence
dar--l         6/19/2026   1:45 PM                scripts
-a---l         6/19/2026   1:48 PM              0 README.md
```

Explanation:

The `ls` command lists the files and folders inside the current folder. This output proves that the project root contains the expected folders and the `README.md` file.

---

## 3. Docs folder structure check

Command used:

```powershell
ls docs
```

Output:

```text
Directory: C:\Users\bryan\OneDrive\Documentos\Dev\developer-toolbox\docs

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
dar--l         6/19/2026   1:48 PM                terminal
```

Command used:

```powershell
ls docs\terminal
```

Output:

```text
Directory: C:\Users\bryan\OneDrive\Documentos\Dev\developer-toolbox\docs\terminal

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---l         6/19/2026   1:48 PM              0 powershell-basics.md
```

Explanation:

This proves that the `docs` folder exists, the `terminal` subfolder exists, and the `powershell-basics.md` file exists.

---

## 4. Scripts folder structure check

Command used:

```powershell
ls scripts
```

Output:

```text
Directory: C:\Users\bryan\OneDrive\Documentos\Dev\developer-toolbox\scripts

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
dar--l         6/19/2026   1:48 PM                powershell
```

Command used:

```powershell
ls scripts\powershell
```

Output:

```text
Directory: C:\Users\bryan\OneDrive\Documentos\Dev\developer-toolbox\scripts\powershell

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---l         6/23/2026   7:48 AM             92 hello-toolbox.ps1
```

Explanation:

This proves that the `scripts` folder exists, the `powershell` subfolder exists, and the `hello-toolbox.ps1` PowerShell script exists.

---

## 5. Evidence folder structure check

Command used:

```powershell
ls evidence
```

Output:

```text
Directory: C:\Users\bryan\OneDrive\Documentos\Dev\developer-toolbox\evidence

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---l         6/23/2026   7:46 AM             90 terminal-evidence.md
```

Explanation:

This proves that the `evidence` folder exists and contains the `terminal-evidence.md` file.

---

## 6. PowerShell script execution

Command used:

```powershell
.\scripts\powershell\hello-toolbox.ps1
```

Output:

```text
Hello from my developer toolbox
Current folder:

Path
----
C:\Users\bryan\OneDrive\Documentos\Dev\developer-toolbox
```

Explanation:

The script ran successfully from the project root.

The command uses a relative path:

```powershell
.\scripts\powershell\hello-toolbox.ps1
```

This relative path works because the terminal is currently located in the project root:

```powershell
C:\Users\bryan\OneDrive\Documentos\Dev\developer-toolbox
```

---

# 7. Concepts

## Terminal

A terminal is a text-based interface where I type commands to interact with my computer, navigate folders, create files, inspect project structure, and run scripts.

In real development work, the terminal is used to run commands, use Git, execute scripts, check errors, install tools, and work with projects locally.

---

## Command

A command is an instruction typed into the terminal.

Examples:

```powershell
pwd
ls
cd
mkdir
New-Item
Get-Content
```

Each command tells the computer to do something specific.

For example:

```powershell
pwd
```

shows the current folder.

```powershell
ls
```

lists the files and folders inside the current folder.

---

## Folder

A folder is a container used to organize files and other folders inside the computer.

Example folders in this project:

```text
docs
scripts
evidence
```

Folders help keep the project organized and easier to understand.

---

## File

A file is an individual item that stores information, text, code, documentation, or configuration.

Examples in this project:

```text
README.md
powershell-basics.md
hello-toolbox.ps1
terminal-evidence.md
```

Each file has a specific purpose.

For example:

```text
hello-toolbox.ps1
```

is a PowerShell script file.

---

## Path

A path is the location of a folder or file.

There are two important types of paths:

```text
Absolute path
Relative path
```

---

## Absolute path

An absolute path is the full location from the drive or root folder.

Example:

```powershell
C:\Users\bryan\OneDrive\Documentos\Dev\developer-toolbox
```

This path points directly to the project root from the `C:` drive.

---

## Relative path

A relative path is a location written from the current folder.

Example:

```powershell
.\scripts\powershell\hello-toolbox.ps1
```

This relative path means:

```text
From the current folder, go into scripts, then powershell, then run hello-toolbox.ps1.
```

The relative path works because the terminal is currently located in the project root:

```powershell
C:\Users\bryan\OneDrive\Documentos\Dev\developer-toolbox
```

If the terminal were located in a different folder, the same relative path could fail.

---

## Project root

The project root is the main folder of the project.

For this project, the root is:

```powershell
C:\Users\bryan\OneDrive\Documentos\Dev\developer-toolbox
```

The project root contains the main project folders and files:

```text
README.md
docs
scripts
evidence
```

---

# 8. Module 0–1 Self-check

## What I can do now

* I can open PowerShell.
* I can navigate to my project folder.
* I can check my current folder with `pwd`.
* I can list files and folders with `ls`.
* I can understand the basic project structure.
* I can identify folders and files.
* I can run a PowerShell script using a relative path.
* I can explain terminal, command, folder, file, path, absolute path, and relative path.

---

## Evidence status

Module 0–1 evidence has been completed and saved in:

```powershell
evidence\terminal-evidence.md
```
