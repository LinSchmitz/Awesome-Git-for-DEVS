# 🚀 Awesome Git for DEVS

> A curated list of **useful and powerful Git-related repositories** for developers.  
> No tutorials. No articles. Just the best Git tools, extensions, and open-source projects.

![Stars](https://img.shields.io/github/stars/LinSchmitz/awesome-git-for-devs?style=social)
![License](https://img.shields.io/github/license/LinSchmitz/awesome-git-for-devs)

---

## ✨ What is this?

A hand-picked list of **Git-focused repositories** to help you work faster, smarter, and more efficiently with Git.  
If it's a tool, CLI helper, plugin, or Git-enhancing project—it's welcome here.

> ✅ No articles — just Git repos.  
> ✅ Focused on developers.  
> ✅ Open to contributions!

---

### 🔧 Git Tools & Utilities

- [jesseduffield/lazygit](https://github.com/jesseduffield/lazygit) – Simple terminal UI for Git commands.
- [dandavison/delta](https://github.com/dandavison/delta) – Syntax-highlighting pager for Git and diff output.
- [git-standup](https://github.com/kamranahmedse/git-standup) – Recall what you worked on yesterday.
- [tj/git-extras](https://github.com/tj/git-extras) – Useful Git utilities like `git-squash` and `git-changelog`.

### 🧠 Git Internals & Educational Projects

- [git/git](https://github.com/git/git) – Official Git source code.
- [pluralsight/git-internals-pdf](https://github.com/pluralsight/git-internals-pdf) – Git internals PDF by Scott Chacon.
- [wyag](https://github.com/micropython-utilities/wyag) – "Write Yourself a Git" in Python.

### 🛠 Git Plugins & Extensions

- [tpope/vim-fugitive](https://github.com/tpope/vim-fugitive) – Git plugin for Vim.
- [junegunn/gv.vim](https://github.com/junegunn/gv.vim) – Git commit browser in Vim.
- [ohmyzsh/ohmyzsh](https://github.com/ohmyzsh/ohmyzsh) – Git-enhanced terminal plugins (via themes/plugins).

### 🎯 Workflow & Helpers

- [github/gitignore](https://github.com/github/gitignore) – Collection of `.gitignore` templates.
- [github/hub](https://github.com/github/hub) – GitHub wrapper for Git.
- [git-town/git-town](https://github.com/git-town/git-town) – High-level Git workflow automation.

---

## 📌 Contribution Guide

Want to add a cool Git-related repo?

1. It must be an **open-source Git-related tool/repo** (not just tutorial).
2. Add the link in the appropriate section with a **short description**.
3. Submit a PR 🙌

---

## 📝 License

MIT © [your-username](https://github.com/your-username)

---

> Inspired by [sindresorhus/awesome](https://github.com/sindresorhus/awesome)  
> Maintained with ❤️ by [@your-username](https://github.com/your-username)

---

## ✨ Why This Exists

Most devs learn Git just enough to get by—but Git is a powerhouse once you unlock its real potential.  
This list gathers the _coolest tricks_, _cleanest workflows_, and _lesser-known commands_ for serious devs and open-source lovers.

---

## 📚 Table of Contents

- [⚡ CLI Tips & Tricks](#-cli-tips--tricks)
- [🧠 Must-Know Concepts](#-must-know-concepts)
- [🔁 Workflow Strategies](#-workflow-strategies)
- [🔥 Real-Life Git Fixes](#-real-life-git-fixes)
- [🧪 Internals & Low-Level Hacks](#-internals--low-level-hacks)
- [🧰 Tools, GUIs & Helpers](#-tools-guis--helpers)
- [🎥 Videos & Talks](#-videos--talks)
- [📘 Books & Guides](#-books--guides)
- [💎 Awesome Related Repos](#-awesome-related-repos)
- [🤝 Contributing](#-contributing)
- [📝 License](#-license)

---

## ⚡ CLI Tips & Tricks

- Visualize commit history beautifully:
  ```bash
  git log --oneline --graph --decorate --all
  ```

````

- Use `git stash -p` to interactively stash specific lines.
- Track down where a bug was introduced:

  ```bash
  git bisect start
  ```

- Make a temporary branch:

  ```bash
  git checkout -b temp && ... && git switch -
  ```

---

## 🧠 Must-Know Concepts

- Understanding the **three Git trees**: Working Directory, Index, and HEAD
- [What is a detached HEAD state?](https://git-scm.com/docs/git-checkout#_detached_head)
- How `rebase` rewrites history (and when it’s OK to use it)

---

## 🔁 Workflow Strategies

- GitHub Flow vs GitLab Flow vs GitFlow
- `Trunk-Based Development` explained
- Protecting `main` branch with PR rules
- [Semantic Commits](https://www.conventionalcommits.org/)

---

## 🔥 Real-Life Git Fixes

- Recover from a `git push --force` mistake
- Revert a merge commit:

  ```bash
  git revert -m 1 <commit>
  ```

- Undo that `git reset --hard` using `git reflog`

---

## 🧪 Internals & Low-Level Hacks

- Exploring `.git/objects` and `.git/index`
- Create a blob manually with `git hash-object`
- [Write Your Own Git in Python](https://wyag.thb.lt/)

---

## 🧰 Tools, GUIs & Helpers

- [LazyGit](https://github.com/jesseduffield/lazygit) – terminal UI for Git
- [Delta](https://github.com/dandavison/delta) – beautiful diff output
- [GitLens](https://gitlens.amod.io/) – Git superpowers in VSCode
- [Sourcetree](https://www.sourcetreeapp.com/) – beginner-friendly GUI
- [tig](https://github.com/jonas/tig) – text-mode interface for Git

---

## 🎥 Videos & Talks

- [Git for Ages 4 and Up](https://www.youtube.com/watch?v=1ffBJ4sVUb4)
- [How Git Works (Visualized)](https://www.youtube.com/watch?v=ZDR433b0HJY)
- [Explaining Git with D3.js](https://onlywei.github.io/explain-git-with-d3/)

---

## 📘 Books & Guides

- [Pro Git](https://git-scm.com/book/en/v2) _(Free and official)_
- [Git From the Bottom Up](https://jwiegley.github.io/git-from-the-bottom-up/)
- [Git Internals PDF](https://github.com/pluralsight/git-internals-pdf)

---

## 💎 Awesome Related Repos

- [github/gitignore](https://github.com/github/gitignore) – popular `.gitignore` templates
- [git/git](https://github.com/git/git) – source code of Git
- [sindresorhus/awesome](https://github.com/sindresorhus/awesome) – the OG list
- [ohmyzsh/ohmyzsh](https://github.com/ohmyzsh/ohmyzsh) – terminal plugins including Git

---

## 🤝 Contributing

Found something awesome or helpful?
Feel free to open a PR or issue!

1. Fork the repo
2. Add your link with a short but clear description
3. Submit a pull request ❤️

Read the [CONTRIBUTING.md](CONTRIBUTING.md) for style and format guidelines.

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

> Created and maintained by [@your-username](https://github.com/your-username)
> If you found this useful, star the repo and share it! ⭐

```

---

### ✅ What to do next:
1. Replace `your-username` with your GitHub handle.
2. Add actual resources for each section (let me know, I’ll help!).
3. Create these files:
   - `LICENSE` → [MIT template](https://choosealicense.com/licenses/mit/)
   - `CONTRIBUTING.md` → Want me to write a good one?
4. Push your repo and **promote it**:
   - Post on X/Twitter, Reddit (like r/git), HackerNews, dev.to
   - Tag it with #git, #opensource, #devtools

---


```
````
