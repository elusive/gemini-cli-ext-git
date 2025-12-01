# Gemini Git Tools Extension

A [Gemini CLI](https://github.com/google-gemini/gemini-cli) extension that streamlines your Git workflow. It uses your local Git context to generate Conventional Commit messages and automate Changelog updates using the power of Gemini.

## 🚀 Features

* **`/git-cm`**: Generates a commit message based on your currently staged changes (`git diff --cached`). It strictly follows the [Conventional Commits](https://www.conventionalcommits.org/) specification.
* **`/git-cl`**: Intelligent Changelog updater. It reads your current `CHANGELOG.md` to find the last entry date, fetches the git log since that point, and drafts a new entry following [Keep a Changelog](https://keepachangelog.com/) standards.

## 📦 Installation

### Option 1: Install via GitHub (Recommended)
You can install this extension directly from the repository URL:

```bash
gemini extensions install [https://github.com/elusive/gemini-git-tools](https://github.com/elusive/gemini-git-tools)


