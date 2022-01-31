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
- ⬜ Installing Git and Creating new Repository
- ⬜ Adding a README.md
- ⬜ Committing your work
- ⬜ Uploading new project to Github

---

# Git vs Github

- Git == Version Control System (VCS)

**other eg:** Mercurial, Subversion etc

- Github == Platform for hosting source code

**other eg:** GitLabs, BitBucket etc

Hence  ***Git != Github***

---

# Installling Git

### Windows

```
Just Download Setup (64 bit)
```
  
### Linux (Debian, Ubuntu)

```shell
sudo apt install git
```

### MacOS


```shell
# Must have already been installed if you have Xcode
brew install git
```

Check version by running following command in Terminal   
(Press Win Key and search `terminal`)

```shell
git --version
# Sample Output
# git version 2.35.0

```

---

# What is a Repository

- Project
- Folder
- File

For example:

- A Java Project
- A React Website Project
- An Android Project

Any Project on Github == **Repository or Repo**