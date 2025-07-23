# Git Commands Cheat Sheet and Workflow Guide

[![Git Logo](https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png)](https://git-scm.com/)

Git is a powerful distributed version control system used by developers to manage code history, collaborate on software projects, automate workflows, and maintain clean, versioned codebases. This documentation offers an in-depth guide to foundational and advanced Git commands, GUI integrations, GitHub CLI usage, workflow automation with GitHub Actions, and includes diagrams for visual learners. It is designed as a README.md for easy consumption and navigation.

---
## 1. Setup & Configuration
Before diving in, configure your identity and editor preferences.
These commands Sets global user.name and user.email, plus useful defaults.

```bash
# Set identity (First commit)
git config --global user.name "Alex Johnson"
git config --global user.email "alex@example.com"

# Set default editor
git config --global core.editor "code --wait"

# Enable color output
git config --global color.ui auto
