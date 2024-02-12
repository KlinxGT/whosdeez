# GitHub Branching Project

## Overview

This project is designed to help team members learn and practice the fundamentals of branching in GitHub. By participating in this project, members will gain hands-on experience with branching strategies, merging, and resolving conflicts within a collaborative development environment.

## Getting Started

Before you begin, ensure you have Git installed on your machine. If not, download and install Git from [git-scm.com](https://git-scm.com/).

### Clone the Repository

To get started with the project, clone the repository to your local machine:

```bash
git clone https://github.com/your-repository-url.git
```

Navigate to the project directory:

```bash
cd your-project-name
```

## Branching Strategy

Our project uses the feature-branch workflow. Each new feature should be developed in its own branch, created from the `main` branch.

### Creating a New Branch

To create and switch to a new branch:

```bash
git checkout -b feature-branch-name
```

### Pushing a Branch to GitHub

After making changes in your branch, push it to GitHub:

```bash
git push -u origin feature-branch-name
```

### Pulling Changes from Main

To ensure your feature branch is up to date with the `main` branch, regularly pull changes:

```bash
git checkout main
git pull origin main
git checkout feature-branch-name
git merge main
```

Resolve any merge conflicts that arise before continuing your work.

### Creating a Pull Request

Once your feature is complete, push your branch to GitHub and open a pull request for review.

## Best Practices

- Keep your feature branches short-lived. Merge them into `main` as soon as the feature is complete and has been reviewed.
- Regularly pull changes from `main` to your feature branch to minimize merge conflicts.
- Ensure your commits are meaningful and descriptive.

## Contact

Jacob Vaught: 803-645-9962, jvaught@sc.edu
