# Projet-Collaboratif-Git-GitHub
## 📘 Introduction to DevBoo
DevBook is a collaborative learning project crafted for students, coding bootcampers, and beginners who want to master Git and GitHub workflows—without writing a single line of code.

Rather than building software, participants work together on structured documentation using Markdown files. This project emphasizes:

 Team collaboration

 Version control best practices

Branching, merging & conflict resolution

Real-world Git workflows

DevBook provides a hands-on, realistic environment that mirrors how professional and open-source teams manage shared repositories. Whether you're just starting with Git or looking to sharpen your skills with pull requests and collaborative branching strategies, DevBook is your sandbox for learning by doing.
# Projet-Collaboratif-Git-GitHub
## Why GitHub is Important

GitHub is not just a code hosting platform — it’s a vital tool for every developer or development team. Here’s why:

- **Easier collaboration**: GitHub allows multiple developers to work on the same project while keeping a clear history of who did what and when.
- **Version control**: With Git (the version control system), you can revert to previous versions of your code, compare changes, and track project evolution.
- **Teamwork with branches**: GitHub makes it easy to create branches to test new features without affecting the main code (`main` or `master`).
- **Code review and pull requests**: Developers can submit their changes through pull requests, allowing teammates to review and approve code before merging.
- **Project portfolio**: A well-organized GitHub profile serves as a professional portfolio. Recruiters, clients, or collaborators can see your skills through public projects.
- **Automation (CI/CD)**: GitHub integrates with tools to automate testing, deployment, and more.
- **Open source community**: GitHub is at the heart of modern open source. Contributing to existing projects helps you learn, gain visibility, and be part of a global tech community.

# Git Tips and Tricks

Welcome to the Git Tips and Tricks guide! This document provides useful Git commands and tips to help you manage your projects more efficiently.

## Table of Contents
1. [Stashing Changes](#stashing-changes)
2. [Reverting Commits](#reverting-commits)
3. [Resetting Changes](#resetting-changes)
4. [Branching and Merging](#branching-and-merging)
5. [Viewing History](#viewing-history)
6. [Miscellaneous Tips](#miscellaneous-tips)

## Stashing Changes

Stashing allows you to temporarily save changes that you don't want to commit immediately.

| Command | Description |
|---------|-------------|
| `git stash` | Stash your changes |
| `git stash save "your stash message"` | Stash your changes with a message |
| `git stash list` | List all stashes |
| `git stash apply` | Apply the most recent stash |
| `git stash apply stash@{n}` | Apply a specific stash |
| `git stash drop stash@{n}` | Delete a stash |
| `git stash clear` | Delete all stashes |

## Reverting Commits

Reverting allows you to undo changes introduced by a specific commit.

| Command | Description |
|---------|-------------|
| `git revert <commit-hash>` | Revert a specific commit |
| `git revert HEAD` | Revert the last commit |

## Resetting Changes

Resetting allows you to move the current HEAD to a specified state.

| Command | Description |
|---------|-------------|
| `git reset --soft <commit-hash>` | Soft reset (keeps changes staged) |
| `git reset --mixed <commit-hash>` | Mixed reset (keeps changes unstaged) |
| `git reset --hard <commit-hash>` | Hard reset (discards all changes) |

## Branching and Merging

Branching and merging are essential for managing different lines of development.

| Command | Description |
|---------|-------------|
| `git branch <branch-name>` | Create a new branch |
| `git checkout <branch-name>` | Switch to a branch |
| `git checkout -b <branch-name>` | Create and switch to a new branch |
| `git merge <branch-name>` | Merge a branch into the current branch |
| `git branch -d <branch-name>` | Delete a branch |

## Viewing History

Viewing the commit history helps you understand the evolution of your project.

| Command | Description |
|---------|-------------|
| `git log` | View commit history |
| `git log --graph` | View commit history with a graph |
| `git log -p` | View commit history with changes |
| `git log <file-path>` | View commit history for a specific file |

## Miscellaneous Tips

Here are some additional tips to enhance your Git workflow.

| Command | Description |
|---------|-------------|
| `git status` | View the status of your working directory |
| `git diff` | View changes in your working directory |
| `git diff <file-path>` | View changes in a specific file |
| `git add <file-path>` | Add changes to the staging area |
| `git commit -m "your commit message"` | Commit changes |
| `git push origin <branch-name>` | Push changes to a remote repository |
| `git pull origin <branch-name>` | Pull changes from a remote repository |



## 👥 Team & Roles


# Roles in the Project Team

| Rôle            | Description                                              | Responsabilités principales                      |
|-----------------|----------------------------------------------------------|-------------------------------------------------|
| Oumnia.BASBASSI: project manager  | Coordonne l'équipe, planifie les étapes et s'assure que le projet avance selon les délais.| Maquettes, prototypes, feedback |
| Yassine Maati: Scrum Master | Coordinates the project, plans, manages resources | Planning, monitoring, risk management |
| Houssam Bouajjioune: Developer | Develops features according to specifications | Writes code, unit tests, documents|
| Saad.HAMDI: QA Assurance | Checks the quality and compliance of deliverables | Functional tests, report |

---


## 👤 Roles in a Project Team (by Bob)


In an effective project team, each member plays a key role. Here's a typical breakdown of roles:

- **Project Manager**: Coordinates the team, plans milestones, and ensures the project progresses on schedule.
- **Scrum Master**: Oversees branches, resolves conflicts, and manages pull requests.
- **Developer**: Writes documents (README, CONTRIBUTING, etc.) and ensures content clarity.
- **Observer/Tester**: Reviews contributions, provides feedback, suggests improvements, and ensures overall consistency.

These roles can rotate to allow everyone to develop new skills.

---
