# CONTRIBUTING

When contributing to this repository, please first discuss the change you wish to make via [issues]((https://github.com/Hello-Ship-Code/this_Test_for_github/issues)).

Please note if you are working on a certain issue then make sure to stay active with development.

## Git Commit, Branch, and PR Naming Conventions

When you are working with git, please be sure to follow the conventions below on your pull requests, branches, and commits:

```text
PR: [#ISSUE ID] Title of the PR
Branch: [ISSUE ID]-title-of-the-pr (shorter)
Commit: [[ISSUE ID]] [ACTION]: what was done
```

Examples:

```text
PR: #2 Add Docker container for Postgres
Branch: 2-add-container-postgres
Commit: [2] feat: add docker container for postgres
```

## Prerequisites

## Installation

## Working on New Features

If you want to work on a new feature, follow these steps.

1. Fork the repository
2. Clone your fork
3. Checkout a new branch
4. Do your work
5. Commit
6. Push your branch to your fork
7. Go into github UI and create a PR from your fork & branch, and merge it into upstream MAIN

## Pulling in changes from upstream

You should pull in the changes that we add in daily, preferably before you checkout a new branch to do new work.

```sh
git checkout main
```

```sh
git pull upstream main
```

## Before Submitting a Pull Request

Before submitting a **Pull Request**, you should

1. Check your code safety with Linter and TypeScript, and make sure your code can build successfully.
