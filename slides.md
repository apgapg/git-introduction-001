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
- ⬜ Cloning a Repository
- ⬜ Adding a README.md
- ⬜ Committing your work
- ⬜ Uploading new project to Github

---

# What is Cloning

- Cloning == Creating a copy

Cloning a Repository == Local copy of Repository on your computer

Four ways:

1. Visual Studio Code (VS Code)
2. IntelliJ/Android Studio
3. Terminal
4. Github Desktop

All 4 are equivalent. Use whatever suits you.

---

# VS Code

<img src="https://res.cloudinary.com/canonical/image/fetch/f_auto,q_auto,fl_sanitize,c_fill,w_720/https://ubuntu.com/wp-content/uploads/c9f4/visualstudio_code-card.png" alt="img" height="300" width="300"/>

Popular Open Source IDE. Download and install it from wesbite.


---

# Android Studio

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9c/IntelliJ_IDEA_Icon.svg/1024px-IntelliJ_IDEA_Icon.svg.png" alt="img" height="100" width="100"/>

Community Edition is free to use.

<img src="https://techcrunch.com/wp-content/uploads/2017/02/android-studio-logo.png" alt="img" height="200" width="200"/>

Free to use.

---

# Terminal

- Run following command

```shell
git clone <repo-url>
```

For eg:

```shell
git clone https://github.com/diybyapg/first-project
```

⚠️ Make sure you are in relevant directory

- git - invoke git command
- clone - clone command
- url - the repository url to clone

❓ To see all available commands

`git --help`
---