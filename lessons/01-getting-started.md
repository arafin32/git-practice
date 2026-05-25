# Getting Started with Git

## Prerequisites
- Basic command line knowledge
- Git installed ([Download Git](https://git-scm.com/downloads))
- GitHub account ([Sign up](https://github.com/join))

## Initial Setup
1. Configure your name and email:
   ```sh
   git config --global user.name "Your Name"
   git config --global user.email "you@example.com"
   ```
2. Check your configuration:
   ```sh
   git config --list
   ```

## Creating Your First Repository
1. Create a new folder and initialize Git:
   ```sh
   mkdir my-first-repo
   cd my-first-repo
   git init
   ```
2. Create a README file and make your first commit:
   ```sh
   echo "# My First Repo" > README.md
   git add README.md
   git commit -m "Initial commit"
   ```

---

[Next: Git Basics](02-git-basics.md)
