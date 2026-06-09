# Developer Field Notes

## Description

A personal Git reference site containing commands, workflow reminders, and best practices.

## Features

- Git vs GitHub explanation
- Daily Git workflow
- Common Git commands
- Git ignore reminders
- Static site deployment

## What I Learned

I learned that Git tracks changes locally while GitHub provides remote repository hosting.

## Live Site

Add your GitHub Pages URL here after deployment.

---

## Git Practice Evidence

### git log --oneline
9258084 (HEAD -> main, origin/main) Merge pull request #6 from Alvin0820/feature/responsive-styling
aa8d7db (origin/feature/responsive-styling, feature/responsive-styling) Improve responsive styling
07c3311 Merge pull request #5 from Alvin0820/feature/safety-section
e753058 (origin/feature/safety-section, feature/safety-section) Add safety section for ignored files
27835dd Merge pull request #4 from Alvin0820/feature/command-reference
35979b5 (origin/feature/command-reference, feature/command-reference) Add command reference section
e742c37 Add styles.css file
4b5a30b Add HTML and ReadME file
ea5cbfb Add gitignore file

---

### git log --oneline --graph --all
9258084 (HEAD -> main, origin/main) Merge pull request #6 from Alvin0820/feature/responsive-styling
|
| * aa8d7db (origin/feature/responsive-styling, feature/responsive-styling) Improve responsive styling
|/
07c3311 Merge pull request #5 from Alvin0820/feature/safety-section
|
| * e753058 (origin/feature/safety-section, feature/safety-section) Add safety section for ignored files
|/
27835dd Merge pull request #4 from Alvin0820/feature/command-reference
|
| * 35979b5 (origin/feature/command-reference, feature/command-reference) Add command reference section
|/
e742c37 Add styles.css file
4b5a30b Add HTML and ReadME file
ea5cbfb Add gitignore file

---

### git branch --all
feature/command-reference
feature/responsive-styling
feature/safety-section
main
remotes/origin/feature/command-reference
remotes/origin/feature/responsive-styling
remotes/origin/feature/safety-section
remotes/origin/main