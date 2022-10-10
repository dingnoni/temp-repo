# lecture_note_6.md
---

## git
using distribute
computer A <----> computer B
local computer have server computer's file
---

## Three Staes in Git
- Modified (Working Directory)
- Staged (Staging Area)
- Comitted (git directory)

---

## Git config
- Sustem level: --system option. After all uses and repositories on the system (administrative) 
file: /etc/gitconfig
- Global(user) level: --global option. Affects all repositories of a current user
file: ~/.config/git/config
- Local level: --local option. Specific to the current repositoriey
-file: git/gitconfig


Each level overrides values in the previous level: 
system -> global -> local
---

## $ git config
  git config --global user.name "name" 
  git config --global user.email address@gmail.com 
  git config --global inint.defalutBranch main 
  git config --list git config --list --show-origin
---
## $ git init
Initializing a Repository in an Existing Directory

---

## $ git status
Checking Repository Status

---

## $ git add[file_name]
Adding a new file to be staged (tracked)

## $ git add .
Adding all files to be staged (tracked)

---
## $ git rm - - cached[file_name]
Unstaging a file

---

## nano .gitignore
Ignoring a file.

---

## git commit -m "commit message"

Commit.

---

## git branch -m used_name new_name

Change branch name.
