# version-control
Jomacs DevOps Training (July - December 2024)
# GitHub Basics

Welcome to **GitHub Basics**! This repository is designed to help beginners get started with GitHub, a powerful platform for version control and collaboration. You'll learn the fundamental concepts of GitHub, including repositories, commits, branches, pull requests, and more.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Key Concepts](#key-concepts)
- [Basic Commands](#basic-commands)
- [Working with Branches](#working-with-branches)
- [Collaboration Workflow](#collaboration-workflow)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)

## Introduction

GitHub is a web-based platform that uses Git, a distributed version control system, to help developers collaborate on projects. Whether you're working on open-source projects or collaborating within a team, GitHub provides tools to manage your code efficiently.

## Getting Started

To get started with GitHub, you need to:

1. **Create a GitHub Account:** [Sign up](https://github.com/join) for a free GitHub account.
2. **Install Git:** Download and install Git from [git-scm.com](https://git-scm.com/).
3. **Configure Git:** Set up your username and email in Git using the following commands:

    ```bash
    git config --global user.name "Your Name"
    git config --global user.email "your.email@example.com"
    ```

4. **Create a Repository:** Learn how to create your first repository on GitHub.

## Key Concepts

- **Repository:** A repository (repo) is a storage space where your project files are kept.
- **Commit:** A commit is a snapshot of your repository at a specific point in time.
- **Branch:** A branch is a parallel version of your repository that allows you to work on different features simultaneously.
- **Pull Request:** A pull request (PR) is a request to merge changes from one branch into another.

## Basic Commands

Here are some basic Git commands to get you started:

- **Clone a Repository:**

    ```bash
    git clone <repository-url>
    ```

- **Check Repository Status:**

    ```bash
    git status
    ```

- **Add Changes to Staging:**

    ```bash
    git add <file-name> # Add specific file
    git add .           # Add all changes
    ```

- **Commit Changes:**

    ```bash
    git commit -m "Commit message"
    ```

- **Push Changes to GitHub:**

    ```bash
    git push origin <branch-name>
    ```

## Working with Branches

Branches allow you to develop features, fix bugs, or safely experiment with new ideas in a contained area of your repository.

- **Create a New Branch:**

    ```bash
    git checkout -b <new-branch-name>
    ```

- **Switch to an Existing Branch:**

    ```bash
    git checkout <branch-name>
    ```

- **Merge Branches:**

    ```bash
    git merge <branch-name>
    ```

## Collaboration Workflow

1. **Fork the Repository:** Create a copy of the repository under your GitHub account.
2. **Clone the Forked Repository:** Clone it to your local machine to make changes.
3. **Create a Branch:** Work on your feature or fix in a new branch.
4. **Commit and Push Changes:** Push your branch to GitHub.
5. **Open a Pull Request:** Request to merge your changes into the original repository.

## Resources

- [GitHub Learning Lab](https://lab.github.com/)
- [Pro Git Book](https://git-scm.com/book/en/v2)
- [GitHub Docs](https://docs.github.com/)

## Contributing

Contributions are welcome! Please read our [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to contribute to this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

