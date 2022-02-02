---
# try also 'default' to start simple
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
drawings:
  persist: false
---

# Welcome to Github Fundamentals

DIY by Ayush P Gupta
<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# Topics

This series covers following topics:

- ✅ Creating Github Account
- ✅ Installing Git and Creating new Repository
- ✅ Cloning a Repository
- ⬜ Knowing Working Tree and Commits
- ⬜ Adding a README.md
- ⬜ Committing your work
- ⬜ Uploading new project to Github

---

# .git folder

Every git repository always contains `.git` folder.

- `.git` == Git initialised in Repository
- By default `.git` is hidden/not shown by IDE
- By default `.git` is hidden in directory too

⚠️ Never manipulate the contents of this folder.

---

# Working Tree

- Working Tree == Container(Box) in which your project resides

<img src="/s1.png" width="600"/>

Modification/Addition/Deletion of a file will cause **Working Tree to become dirty**

Run `git status` to check tree status

---

# Stage/Staging - 1

- Run `git status` in project:

```
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
```
  

- After editing a file:

```
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
```

---

# Stage/ Staging - 2

- Staging changes == Prepare changes for modification

- Only those changes will be included by which are in **staged** condition.

- Why **Stage** option exist? So as to not include all changed files

To stage changes, Run:

```
git add .
```

This will mark all changes as staged and prepare them for commit.

---

# Discard Changes

- To remove the changes done locally
- Make working tree clean

⚠️ Always use IDE for discarding changes to have better visibility.