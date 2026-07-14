# Git-and-GitHub-Tutorial

## Learn the Basics

A Version Control System (VCS) is a tool that tracks code changes over time. It helps developers manage different versions of a project, collaborate with others, and maintain a history of all modifications.

## What is Version Control?

Version control is a system that tracks changes to files over time. It allows developers to view change history, restore previous versions, collaborate safely, and prevent work from being overwritten.

## Why Use Version Control?

Version control tracks every change to a project, allows developers to restore previous versions, eliminates the need for manual backups, enables team collaboration, and records each change with a commit message.

## Git vs Other VCS

Git is a distributed version control system (DVCS), where each developer has a complete copy of the project history. Unlike centralized systems such as SVN or CVS, Git supports offline commits, branching, and history browsing, while syncing with a remote repository only when pushing or pulling.

## Installing Git Locally

Install Git on your computer using the appropriate method for your operating system. After installation, run `git --version` in the terminal to verify that Git is installed correctly.

## What is a Repository?

A repository is a storage location for a project's code, documentation, and other files. It helps manage versions, supports collaboration, and keeps all project resources organized in one place.

### git init

The `git init` command creates a new Git repository. It initializes an existing project or a new empty directory so Git can start tracking changes.

### git config

The `git config` command sets Git configuration values such as the user name, email, and default editor. These settings are used to identify commits and customize Git behavior.

### Local vs Global Config

Git configuration can be set locally for a single repository or globally for all repositories of a user. Local settings override global settings when both are defined.

### Working Directory

The working directory is the project folder where files are created and edited. It contains the current state of the project, including changes that have not yet been staged or committed.

### Staging Area

The staging area is where changes are prepared before a commit. The `git add` command moves selected changes from the working directory to the staging area, allowing developers to choose what to include in the next commit.

### Committing Changes

A commit saves the staged changes to the repository history with a descriptive message. Each commit has a unique hash, allowing Git to track, compare, and restore project versions.

### .gitignore

The `.gitignore` file specifies files and folders that Git should ignore. It contains patterns that prevent unnecessary or sensitive files from being tracked in the repository.

### Viewing Commit History

The `git log` command displays the commit history of a repository. It shows each commit's hash, author, date, and message, helping developers review changes and track project history.

## Branching Basics

Branches are separate lines of development that allow developers to work on features or fixes without affecting the main codebase. They support collaboration, isolated development, and organized workflows.

### Creating Branch

Creating a branch allows developers to work on new features or fixes without affecting the main codebase. Branches can be created using Git commands or the GitHub interface.

### Renaming Branch

Renaming a branch changes its name without affecting its commit history or code. Only the branch reference is updated, while all existing changes and history remain intact.

### Deleting Branch

Deleting a branch removes its reference from the repository. It is commonly done after a branch has been merged and is no longer needed.

### Checkout Branch

Checking out a branch switches the working directory to that branch. It makes the selected branch active and updates the project files to match its current state.

### Merging Basics

A merge combines changes from one branch into another. Git integrates the updates, resolves conflicts if necessary, and creates a commit that represents the combined changes.

## GitHub Essentials

GitHub Essentials covers the basic features of GitHub, including creating an account, setting up a profile, understanding the interface, and creating repositories for online collaboration.

### Creating Account

Create a free personal account on GitHub, verify your email address, and set up your username and profile to start using GitHub.

### GitHub Interface

The GitHub interface is the web dashboard for managing repositories, files, commits, pull requests, issues, notifications, and project settings.

### Setting up Profile

Set up your GitHub profile by adding a profile picture, bio, location, and useful links. You can also pin repositories to showcase your important projects.

### Profile README

A Profile README is a special repository named after your GitHub username. GitHub automatically displays its README on your profile, allowing you to showcase your skills, projects, badges, and contact information.

### Creating Repositories

Creating a repository sets up a project for version control. It allows you to store files, track changes, manage code, and collaborate with other developers.

### Private vs Public

A public repository is accessible to everyone, while a private repository is limited to the owner and invited collaborators. Public repositories are ideal for open source projects, whereas private repositories are suitable for private or ongoing work.

### Git Remotes

A Git remote is a repository hosted on a remote server, such as GitHub. It allows developers to push local changes, pull updates, and collaborate through a shared repository. The default remote is usually named `origin`.

## Git Remotes

A Git remote is a repository hosted on a remote server, such as GitHub. It allows developers to push local changes, pull updates, and collaborate through a shared repository. The default remote is usually named `origin`.

### Fetch without Merge

The `git fetch` command downloads commits, branches, and tags from a remote repository without merging them into the current branch. It updates remote-tracking branches, allowing developers to review changes before merging.

### Pushing / Pulling Changes

The `git pull` command fetches and merges changes from a remote repository into the local branch. The `git push` command uploads local commits to a remote repository, making the latest changes available to others.

### Managing Remotes

Managing remotes allows you to add, rename, remove, and view remote repositories. Use `git remote add` to add a remote, `git remote rename` to rename it, `git remote remove` to delete it, and `git remote -v` to list all configured remotes.

### Cloning Repositories

Cloning a repository creates a local copy of a remote repository. It allows developers to work on the project locally, commit changes, and push updates back to the remote repository.

## Merge Strategies

Merge strategies define how Git combines changes from one branch into another. Common strategies include standard merge, squash merge, and rebase, each producing a different commit history.

### Fast-Forward vs Non-FF

A fast-forward merge moves the branch pointer forward without creating a new commit. A non-fast-forward merge creates a merge commit to combine two branch histories, even when they have diverged.

### Rebase

Rebase moves or reapplies commits from one branch onto another, creating a cleaner and more linear commit history while integrating changes.

### Squash

Squash combines multiple commits into a single commit, creating a cleaner and more concise commit history before merging changes into another branch.

### Handling Conflicts

Merge conflicts occur when changes from different branches overlap. Git marks the conflicting sections, and developers must manually resolve them before completing the merge.

### Cherry Picking Commits

Cherry-picking applies a specific commit from one branch to another without merging the entire branch. It is useful for copying individual fixes or features between branches.

## Collaboration on GitHub

GitHub enables multiple developers to collaborate on the same project using Git. It provides tools such as pull requests, code reviews, issues, and discussions to support organized teamwork.

### Forking vs Cloning

Forking creates a personal copy of a repository on your GitHub account, while cloning downloads a repository to your local machine. A common workflow is to fork a repository, clone it locally, make changes, and submit a pull request.

### Issues

Issues are used to track bugs, feature requests, and tasks in a repository. They include a title, description, comments, and optional labels, assignees, and milestones to help organize project work.

### Pull Requests

A pull request is a proposal to merge changes from one branch into another. It allows collaborators to review, discuss, and approve changes before they are merged into the target branch.

### PR from a Fork

A pull request from a fork allows contributors to propose changes to a repository without direct write access. Contributors fork the repository, make changes in their own copy, and submit a pull request to the original repository.

### Collaborators

Collaborators are GitHub users who have been granted access to a repository. Depending on their permissions, they can push commits, create branches, and manage issues and pull requests.

### Labelling Issues / PRs

Labels are colored tags used to categorize issues and pull requests by type, priority, or status. They help organize, filter, and manage project tasks more efficiently.

### Saved Replies

Saved replies are reusable comment templates for issues and pull requests. They help users respond quickly with consistent messages and can be customized from GitHub settings.

### Mentions

Mentions notify specific users or teams by using `@username` or `@teamname` in comments, issues, or pull requests. They help improve collaboration and ensure the right people are involved in discussions.

### Reactions

Reactions allow users to respond to issues, pull requests, and comments using emojis. They provide a quick way to express feedback without adding extra comments.

### GitHub Discussions

GitHub Discussions is a forum-style feature for sharing questions, ideas, and announcements. Unlike issues, discussions are designed for open conversations rather than tracking specific tasks.

## Best Practices

Follow Git and GitHub best practices to maintain clean, organized, and collaborative projects. Use meaningful commits, proper branching, code reviews, and secure file management.

### Code Reviews

Code reviews involve examining changes in a pull request before merging. Reviewers can identify issues, suggest improvements, approve changes, and help maintain code quality across a team.

### PR Guidelines

PR guidelines define the rules for submitting pull requests. They usually include writing clear descriptions, keeping changes focused, and linking related issues to make reviews easier.

### Branch Naming

Branch naming conventions provide a consistent way to name branches using prefixes like `feature/`, `bugfix/`, and `hotfix/`. Clear naming helps identify branch purposes and improves team workflow.

### Commit Messages

Commit messages describe the changes made in a commit. Clear and informative messages help developers understand the purpose of changes and maintain an organized project history.

### Contribution Guidelines

Contribution guidelines define the rules and processes for contributing to a project. They help maintain code quality, consistency, and effective collaboration among developers.

### Clean Git History

A clean Git history contains organized commits with clear messages and minimal unnecessary changes. Techniques like squashing, rebasing, and meaningful commits make project history easier to understand and maintain.

## Documentation

Documentation explains how a project works, how to use it, and how to contribute. It includes README files, wikis, and other resources that help users and contributors understand the repository.

### CITATION Files

A `CITATION.cff` file provides citation information for a repository. It helps others properly cite and reference your work using human- and machine-readable metadata.

### GitHub Wikis

GitHub Wikis provide a separate space for detailed documentation, tutorials, and notes. They support Markdown and maintain their own version history, making them useful for guides, FAQs, and design documents.

### Project README

A README is the main documentation file of a repository. It explains the project's purpose, setup instructions, usage, examples, and contribution guidelines using Markdown.

### Markdown

Markdown is a lightweight markup language used to format text with simple syntax. GitHub automatically renders Markdown in README files, issues, pull requests, and comments for readable documentation.

## Working in a Team

Working in a team on GitHub involves managing collaborators, roles, permissions, and communication. Organizations and teams help multiple developers collaborate efficiently on shared projects.

### Collaborators / Members

Collaborators are users who are granted permission to contribute to a repository. Members, especially within organizations, manage access and permissions based on their roles in the team.

### GitHub Organizations

A GitHub organization is a shared account for managing multiple repositories, members, and teams. It provides centralized permission management, billing, and access control for collaborative projects.

### Teams within Organization

Teams in a GitHub organization group members together to manage repository permissions efficiently. Assigning access to a team allows all members to inherit the same permissions.

## GitHub Projects

GitHub Projects is a project management tool built into GitHub.

It helps teams organize and track their work using boards, tables, and timelines. You can manage issues and pull requests, create custom fields, and automate tasks.

GitHub Projects can track work from one or multiple repositories. It is useful for planning sprints, monitoring progress, and managing tasks without leaving GitHub.

### Project Planning

Project planning in GitHub Projects helps teams organize their work before starting.

Teams can create project boards, add custom fields, set milestones, prioritize issues, and assign tasks to team members or sprints.

Good planning helps track progress, manage tasks, and find problems before deadlines.

### Kanban Boards

A Kanban board is a visual way to organize tasks.

Tasks are placed in columns such as **To Do**, **In Progress**, and **Done**. As work moves forward, tasks are moved to the next column.

GitHub Projects includes a Kanban board where you can drag and drop issues and pull requests to track progress easily.

### Roadmaps

GitHub Roadmaps help teams plan and organize project goals and milestones.

They provide a high-level view of the project, making it easy to track progress and collaborate with team members.

### Automations

GitHub Projects supports automation to reduce manual work.

You can automatically update fields, archive completed items, and add issues or pull requests to a project based on rules.

## Git Stash Basics

Git stash temporarily saves uncommitted changes without creating a commit.

Use `git stash` to save your current work and clean the working directory. Later, use `git stash pop` to restore the saved changes.

This is useful when you need to switch branches or pull updates without losing your work.

# Intermediate topics

## History

Git history is a record of all commits in a repository.

Each commit stores file changes, a commit message, and other information. Every commit is saved as a snapshot, creating a new version of the project.

### Linear vs Non-Linear

A linear history has commits in a single straight line with no merge commits. It is usually created by using rebase.

A non-linear history includes branches and merge commits, showing how work happened in parallel.

Teams choose linear history for a clean commit log or non-linear history to keep the full development history.

### HEAD

HEAD is a special reference that points to the current branch or commit in Git.

Normally, HEAD points to the current branch. When you check out a specific commit or tag, HEAD points directly to that commit. This is called a **detached HEAD** state.

### Detached HEAD

A detached HEAD happens when HEAD points to a specific commit instead of a branch.

You can view old commits without changing the current branch. If you make new commits in this state, create a new branch to save them before switching branches.

### git log Options

The `git log` command has many options to view commit history in different ways.

For example, `--oneline` shows a short history, `--graph` displays branches and merges, and filters like `--author` or `--since` show specific commits.

These options make it easier to find the information you need in a Git repository.

## Undoing Changes

Git provides different ways to undo changes.

Use `git checkout` to discard local changes, `git reset` to unstage changes or remove commits, and `git revert` to safely undo a commit that has already been shared.

Choose the correct command based on whether the changes have been pushed to a remote repository.

### git revert

`git revert` creates a new commit that reverses the changes made by an earlier commit.

It does not change the existing commit history, making it safe for shared branches.

Use `git revert <commit-hash>` to undo a specific commit by creating a new commit.

### git reset

`git reset` moves the HEAD pointer to a previous commit.

It has three modes:

- **--soft** keeps changes in the staging area.
- **--mixed** removes changes from staging but keeps them in the working directory.
- **--hard** removes commits, staging changes, and working directory changes.

Choose the mode based on how much you want to undo.

## Viewing Diffs

Viewing diffs helps you see the changes made to your code.

Diffs show which lines were added, modified, or removed between different versions of a file.

This is useful for code reviews, debugging, and tracking project history. Git provides commands to compare and manage changes easily.

### Between Commits

Use `git diff <commit1> <commit2>` to compare two commits.

It shows the lines that were added, modified, or deleted between the selected commits.

This helps you understand the changes made between two versions of your project.

### Between Branches

Use `git diff <branch1>..<branch2>` to compare two branches.

It shows the changes made between the branches, including added, modified, and deleted lines.

This is useful for reviewing changes before merging a feature branch into the main branch.

### Staged Changes

Use `git diff --cached` to view staged changes.

This command compares staged files with their previous versions in the repository.

It helps you review your changes before creating a commit.

### Unstaged Changes

Use `git diff` to view unstaged changes.

This command compares your working directory with the staging area and shows changes that have not been staged.

It helps you review local changes before adding them to the staging area.

## Rewriting History

Rewriting history changes existing commits instead of creating new ones.

Examples include changing a commit message with `git commit --amend` or modifying commits with `git rebase`.

These operations change commit hashes, so they are safe for local branches but should be avoided on shared branches.

### git commit --amend

`git commit --amend` is used to modify the most recent commit.

You can change the commit message, add or remove files, or update commit information.

Git replaces the last commit with a new one that includes the latest changes.

### git rebase

`git rebase` moves commits from one branch on top of another branch.

Unlike `git merge`, it does not create a merge commit. Instead, it rewrites the commit history to create a clean and linear history.

`git rebase` is best used on local or unshared branches.

### git filter-branch

`git filter-branch` rewrites the history of a Git repository.

It is used to remove sensitive files, delete unwanted files from all commits, or change project history.

Because it is slow and can be error-prone, Git now recommends using `git filter-repo` as a faster and safer alternative.

### git push --force

`git push --force` replaces the remote branch history with your local branch history.

It is commonly used after rewriting commits with commands like `git rebase`.

Because it can overwrite other people's work, `git push --force-with-lease` is usually a safer choice.

## Tagging

Tagging marks an important commit in Git, usually for release versions such as `v1.0.0`.

Tags do not move when new commits are added, so they always point to the same commit.

Git supports two types of tags: **lightweight** tags and **annotated** tags.

### Managing Tags

Managing tags includes creating, viewing, and deleting tags in a Git repository.

Use `git tag <name>` to create a lightweight tag and `git tag -a <name> -m "message"` to create an annotated tag.

Run `git tag` to list all tags and `git tag -d <name>` to delete a local tag.

### Pushing Tags

Pushing tags sends your local Git tags to a remote repository.

Tags are commonly used to mark releases and important milestones.

After pushing, other team members can access and use the same tags.

### Checkout Tags

Checking out a tag switches your repository to the state of a specific tagged commit.

Tags are usually used for release versions or important milestones.

When you check out a tag, Git places you in a detached HEAD state, allowing you to view or test that version of the project.

### GitHub Releases

GitHub Releases are created from a specific Git tag.

A release can include release notes, binaries, and other downloadable files.

Releases help users download a specific version, share software, and view changes between versions.

## Git Hooks

Git hooks are scripts that run automatically during Git operations.

They are stored in the `.git/hooks` directory and can be written in any supported scripting language.

Git hooks are commonly used to run tests, check code, or trigger deployments automatically.

### pre-push

The `pre-push` hook runs before changes are pushed to a remote repository.

It is commonly used to run tests or check that the branch is up to date.

If the hook script returns a non-zero exit status, the push is cancelled.

### pre-commit

The `pre-commit` hook runs before a commit is created.

It is commonly used to run linters, formatters, or tests on staged changes.

If the hook script returns a non-zero exit status, the commit is cancelled.

### post-update

The `post-update` hook runs on the remote repository after a successful push.

It is used to automate server-side tasks such as triggering CI, updating services, sending notifications, or starting deployments.

This hook helps automate workflows and improve team collaboration.

### post-checkout

The `post-checkout` hook runs after a successful `git checkout` command.

It can update dependencies, regenerate files, or change project settings for the new branch.

This hook helps automate tasks and keep the project consistent across branches.

### commit-msg

The `commit-msg` hook runs after you enter a commit message and before the commit is created.

It is used to validate or modify the commit message.

This hook helps enforce commit message rules and maintain a consistent commit history.

## Git Patch

A Git patch is a file that contains changes made to a project.

It shows the differences between two versions, including added, modified, and deleted lines.

Although patches are used less today because of modern Git workflows, they are still useful for sharing and applying code changes.

## Submodules

A submodule is a Git repository inside another Git repository.

It keeps its own commit history and allows a project to use a specific version of another repository.

Submodules are commonly used for shared libraries and project dependencies.

### Adding / Updating Submodules

Use `git submodule add <repository-url>` to add a submodule to your repository.

Use `git submodule update` to update an existing submodule.

If the submodule URL changes, run `git submodule sync` followed by `git submodule update` to synchronize and update the submodule.

### What and Why use Submodules?

Submodules let a Git repository use another repository at a specific commit instead of copying its code.

They are useful for sharing libraries or dependencies between multiple projects.

Submodules keep the dependency's history separate while allowing the main project to use a fixed version.

# GitHub WorkFlow

## GitHub CLI

GitHub CLI (`gh`) is a command-line tool for working with GitHub.

It lets you create repositories, manage issues, and open pull requests directly from the terminal.

It is also useful for automating GitHub tasks in scripts and CI/CD pipelines.

### Installation and Setup

Install GitHub CLI (`gh`) using a package manager like Homebrew, apt, or winget based on your operating system.

After installation, run:

`gh auth login`

to connect GitHub CLI with your GitHub account.

Once authenticated, you can use `gh` commands to manage GitHub directly from the terminal.

### Repository Management

GitHub CLI provides commands to manage repositories from the terminal.

Examples:

- `gh repo create` creates a new repository.
- `gh repo clone` clones a repository.
- `gh repo view` shows repository details.

These commands allow developers to manage GitHub repositories without using the web interface.

### Repository Management

GitHub CLI provides commands to manage repositories directly from the terminal.

Examples:

- `gh repo create` creates a new repository.
- `gh repo clone` clones a repository.
- `gh repo view` displays repository details.

These commands help developers manage GitHub repositories without using the web interface.

### Issue Management

GitHub CLI allows developers to create, view, and manage issues from the terminal.

Examples:

- `gh issue create` creates a new issue.
- `gh issue list` displays repository issues.

Issues can be filtered by label, assignee, or state, making issue management easier without using the browser.

### Pull Requests

GitHub CLI supports the complete pull request workflow from the terminal.

Examples:

- `gh pr create` creates a pull request.
- `gh pr diff` shows pull request changes.
- `gh pr merge` merges a pull request.

It helps developers manage pull requests without leaving the terminal or code editor.

### Use in Automation

GitHub CLI can automate GitHub tasks inside scripts and CI/CD pipelines.

It can create releases, comment on issues, and trigger workflows automatically.

With token-based authentication, it can run in non-interactive environments without manual login.

## GitHub Actions

GitHub Actions is a CI/CD platform built into GitHub.

It automates tasks like testing, building, and deploying code based on repository events.

Workflows are written in YAML files inside the `.github/workflows` directory and can run on GitHub-hosted or self-hosted runners.

### Use Cases

GitHub Actions can automate many development and operations tasks.

Common uses include:

- Running tests on every pull request.
- Building and deploying applications.
- Publishing packages.
- Sending notifications.
- Automating repository maintenance tasks.

Workflows can be triggered by GitHub events, making automation flexible and powerful.

### What are these?

GitHub Actions helps developers automate tasks based on repository events.

When events like pushing code or creating a pull request happen, workflows automatically run defined tasks such as testing or deployment.

This reduces manual work and ensures consistent checks every time.

### YAML Syntax

GitHub Actions workflows are written in YAML format.

YAML uses indentation to define structure instead of brackets or tags.

Common workflow keys:

- `on` defines triggers.
- `jobs` defines tasks to run.
- `steps` defines commands inside each job.

Correct indentation is important because YAML is sensitive to spacing.

### Workflow Triggers

Workflow triggers are events that start a GitHub Actions workflow.

Triggers can run workflows when code changes happen, at scheduled times, or manually.

They help automate tasks based on specific conditions.

### Scheduled Workflows

Scheduled workflows run automatically at specific times using the `schedule` trigger with cron syntax.

They are useful for tasks like nightly builds, cleanup jobs, and regular data updates.

GitHub schedules workflows using UTC time, and execution may have a small delay depending on runner availability.

### Workflow Runners

Workflow runners are environments where GitHub Actions workflows run.

There are two types of runners:

- **GitHub-hosted runners** use virtual machines provided by GitHub.
- **Self-hosted runners** run on machines managed by users or organizations.

Each runner has different configurations and capabilities based on its type.

### Workflow Context

Workflow context provides information and variables available during a GitHub Actions workflow run.

It includes details about the event that triggered the workflow, the repository, and the workflow execution.

Contexts help workflows access dynamic information and make decisions during execution.

### Secrets and Env Vars

Secrets store sensitive information like API keys, passwords, and tokens securely.

Environment variables, defined using the `env` key, store configuration values used during workflow execution.

Using both keeps sensitive data out of workflow files while still making required values available when needed.

### Caching Dependencies

Caching dependencies stores files like package manager directories between workflow runs.

The `actions/cache` action saves and restores cached files using a key, often based on a lockfile hash.

Caching reduces installation time and makes GitHub Actions workflows run faster.

### Storing Artifacts

Artifacts are files created during a GitHub Actions workflow, such as build outputs, test reports, and logs.

Use `actions/upload-artifact` to save files and `actions/download-artifact` to retrieve them later.

Artifacts help share files between jobs and keep workflow results available for review.

### Workflow Status

Workflow status shows whether a GitHub Actions run is successful, failed, or still running.

Statuses are displayed on commits, pull requests, and the Actions tab.

Required status checks can prevent merging until workflows pass, helping ensure code quality before merging.

### Marketplace Actions

Marketplace Actions are reusable workflow steps created by GitHub and the community.

They can be added to workflows for common tasks like checking out code or setting up programming languages.

Examples:

- `actions/checkout` checks out repository code.
- `actions/setup-node` sets up Node.js.

Using marketplace actions saves time and improves workflow reliability.

# Advance topic

## Git Reflog

Git reflog records changes to branches and references like `HEAD`.

It stores actions that may not appear in the normal commit history, such as resets and checkouts.

Reflog is useful for recovering lost commits and understanding changes made in a repository.

`reflog` stands for "reference log".

## Git Bisect

Git Bisect helps find the commit that introduced a bug or regression.

It uses a binary search approach between:

- A **good** commit where the bug does not exist.
- A **bad** commit where the bug exists.

Commands:

- `git bisect start` starts the process.
- `git bisect good <commit>` marks a working commit.
- `git bisect bad <commit>` marks a broken commit.

Git checks commits between them until it finds the exact commit that caused the bug.

## Git Worktree

Git worktree allows multiple branches to be checked out at the same time in different directories.

Use:

`git worktree add <path> <branch>`

to create a new working directory for a branch without cloning the repository again.

It is useful when working on multiple branches, such as developing a feature while testing a hotfix.

## Git Attributes

Git attributes are settings stored in the `.gitattributes` file.

They control how Git handles files, including filtering, conversion, and formatting.

Example:

```text
*.txt text
*.jpg binary
```

## Git LFS

Git Large File Storage (LFS) helps manage large files in Git.

Instead of storing large files directly in the repository, Git stores metadata while the actual file content is stored separately.

Git LFS is useful for:

- Images
- Videos
- Audio files
- Large datasets
- Game development assets

It improves clone and push performance, but requires separate storage for the actual file content.

## Webhooks

GitHub Webhooks send real-time notifications when events happen in a repository.

They can respond to events like:

- Commits
- Pull requests
- Issues

Webhooks help automate tasks, connect GitHub with other services, and create custom workflows.

## GitHub API

GitHub API allows developers to interact with GitHub using code.

It provides access to features like:

- User data
- Repository information
- Commit history
- Issues and pull requests

GitHub API supports REST and GraphQL interfaces.

It includes authentication, rate limiting, and webhooks for building automation, integrations, and custom applications.

### GraphQL API

GitHub GraphQL API allows developers to interact with GitHub using GraphQL queries.

It provides access to GitHub features such as:

- User data
- Repository information
- Commit history

Developers can use GraphQL to retrieve and manage GitHub data programmatically.

### REST API

GitHub REST API allows developers to interact with GitHub using HTTP requests.

It provides access to features such as:

- User data
- Repository information
- Commit history

Developers can use REST API to automate tasks and build applications that work with GitHub.

## Creating Apps

GitHub Apps allow developers to integrate with GitHub programmatically.

They can use REST API or GraphQL API to:

- Automate tasks.
- Send real-time notifications.
- Create custom workflows.

GitHub Apps help build custom integrations that extend GitHub functionality.

### OAuth Apps

GitHub OAuth Apps allow applications to connect with GitHub using OAuth 2.0 authentication.

They provide secure token-based access to GitHub resources like:

- Repositories
- Issues
- Pull requests

OAuth Apps allow users to approve specific permissions without sharing their passwords.

They can automate tasks, personalize interactions, and receive real-time notifications.

### GitHub Apps

GitHub Apps allow developers to integrate with GitHub programmatically.

They can use REST API or GraphQL API to:

- Automate tasks.
- Provide real-time notifications.
- Build custom workflows.

GitHub Apps help create powerful integrations that extend GitHub functionality.

# more github features

## GitHub Pages

GitHub Pages allows users to host and publish websites directly from a GitHub repository.

It can be used to create:

- Websites
- Blogs
- Project documentation
- Portfolio pages

GitHub Pages provides simple deployment without manual server configuration and supports themes and customization options.

### Deploying Static Websites

GitHub Pages can host static websites that contain pre-built files like HTML, CSS, and JavaScript.

Static website deployment provides:

- Fast deployment
- Low maintenance
- Better security

It is commonly used for portfolios, blogs, and documentation websites.

### Custom Domains

GitHub Pages allows users to connect a custom domain to their website.

Instead of using the default `github.io` URL, users can use their own domain name.

Custom domains provide:

- A professional website address
- Better branding
- A personalized web presence

### Static Site Generators

Static Site Generators (SSGs) create websites by generating static HTML files from content and templates.

GitHub Pages supports popular SSGs like:

- Jekyll
- Hugo
- Middleman

SSGs make it easy to build and deploy websites without complex configuration or maintenance.

### GitHub Gists

GitHub Gists are small code or text snippets that can be shared easily.

They are useful for sharing:

- Code examples
- Configuration files
- Scripts
- Tutorials

Each gist has a unique URL and supports features like:

- Syntax highlighting
- Line numbers
- Commit history

Gists allow developers to share content without creating a full repository.

### GitHub Packages

GitHub Packages is a package hosting service that allows developers to publish and manage software packages directly on GitHub.

It supports packages such as:

- npm
- Docker
- Maven
- NuGet

GitHub Packages uses repository permissions to control package access.

It helps teams manage source code and published packages together on the same platform.

### GitHub Codespaces

GitHub Codespaces provides a cloud-based development environment that runs directly from a repository.

It includes:

- Code editor
- Terminal
- Tools and dependencies

The environment is configured using a `devcontainer.json` file.

Codespaces allows developers to start coding quickly without installing tools locally and provides a consistent setup for teams.

### GitHub Security

GitHub Security provides built-in tools to find and fix vulnerabilities in repositories.

Security features include:

- Dependency scanning
- Secret scanning
- Code scanning

These tools can detect vulnerable packages, exposed secrets, and security issues in code.

Security checks can run with pull requests to identify problems before merging changes.

### GitHub Sponsors

GitHub Sponsors allows developers and organizations to receive financial support for their open source work.

Sponsors can provide:

- One-time contributions
- Monthly recurring payments

Maintainers can create sponsorship tiers with different benefits.

GitHub Sponsors helps open source developers earn income and continue maintaining their projects.

### GitHub Copilot

GitHub Copilot is an AI-powered code completion tool that helps developers write code faster.

It provides context-aware suggestions and can generate:

- Functions
- Methods
- Classes
- Code snippets

Copilot reduces coding time by suggesting relevant code and helps developers focus on design and problem-solving.

### GitHub Models

GitHub Models allows developers to discover, explore, and use pre-trained AI models from different sources.

It helps developers:

- Find AI models quickly.
- Experiment with different models.
- Add AI capabilities to applications.

GitHub Models saves time by allowing developers to use existing models instead of training models from scratch.

### GitHub Marketplace

GitHub Marketplace allows developers to discover, install, and manage third-party tools and services inside GitHub.

It provides tools for:

- Code analysis
- Project management
- Collaboration
- Automation

Using GitHub Marketplace helps developers improve workflows and focus more on building software.

### GitHub Education

GitHub Education provides free and discounted access to GitHub tools and resources for students, teachers, and researchers.

It helps users:

- Learn software development.
- Build real-world projects.
- Collaborate with others.
- Gain practical coding experience.

GitHub Education supports a better learning environment for software development and research.

### Student Developer Pack

GitHub Student Developer Pack provides free and discounted access to developer tools and resources for students.

It includes:

- GitHub
- GitHub Desktop
- GitHub Classroom
- Developer learning resources

The pack helps students gain practical experience with professional tools and build real-world software projects.

### GitHub Classroom

GitHub Classroom helps educators create and manage coding assignments, projects, and quizzes for students.

It allows teachers to:

- Share coding tasks.
- Review student code.
- Provide feedback.
- Track student progress.

GitHub Classroom promotes collaboration and hands-on learning using real-world development workflows.

### Campus Program

GitHub Campus Program provides free access to GitHub Enterprise Cloud and GitHub Enterprise Server for eligible schools.

It helps students and educators:

- Build software projects.
- Collaborate effectively.
- Learn professional development skills.
- Use advanced developer tools.

The program supports educational communities with resources and GitHub services.
