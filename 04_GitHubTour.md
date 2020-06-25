# GitHub Interface Tour and Jargon Busting




## Glossary

Definitions are from the [GitHub Glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary#pull), with some minor edits and additions from me:

- **branch** - A branch is a parallel version of a repository. It is contained within the repository, but does not affect the primary or ~~master~~ default branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the ~~master~~ default branch to publish your changes.
- **clone** - A clone is a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. When you make a clone, you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. The repository you cloned is still connected to the remote version so that you can push your local changes to the remote to keep them synced when you're online.
- **code of conduct** - A document that defines standards for how to engage in a community.
- **collaborator** - A collaborator is a person with read and write access to a repository who has been invited to contribute by the repository owner.
- **commit** - A commit, or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes commited along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.
- **commit message** - Short, descriptive text that accompanys a commit and communicates the change the commit is introducing.
- **contributor** - A contributor is someone who does not have collaborator access to a repository but has contributed to a project and had a pull request they opened merged into the repository.
- **default branch** - The base branch in your repository, against which all pull requests and code commits are automatically made, unless you specify a different branch. This branch is usually called `master`.
   - Although the current default base branch on GitHub is the `master` branch, [GitHub is working on changing it to a neutral term](https://www.bbc.co.uk/news/technology-53050955) such as `main`.
- **diff** - A diff is the difference in changes between two commits, or saved changes. The diff will visually describe what was added or removed from a file since its last commit.
- **fork** - A fork is a personal copy of another user's repository that lives on your account. Forks allow you to freely make changes to a project without affecting the original upstream repository. You can also open a pull request in the upstream repository and keep your fork synced with the latest changes since both repositories are still connected.
- **Git** - Git is an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.
- **GitHub Pages** - Also referred to as Pages. A static site hosting service designed to host your personal, organization, or project pages directly from a GitHub repository.
- **issue** - Issues are suggested improvements, tasks or questions related to the repository. Issues can be created by anyone (for public repositories), and are moderated by repository collaborators. Each issue contains its own discussion thread. You can also categorize an issue with labels and assign it to someone.
- **license** - A document that you can include with your project to let people know what they can and can't do with your source code.
- **Markdown** - Markdown is an incredibly simple semantic file format, not too dissimilar from .doc, .rtf and .txt. Markdown makes it easy for even those without a web-publishing background to write prose (including with links, lists, bullets, etc.) and have it displayed like a website. GitHub supports Markdown and uses a particular form of Markdown called GitHub Flavored Markdown. See [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) or [Getting started with writing and formatting on GitHub](https://help.github.com/en/articles/getting-started-with-writing-and-formatting-on-github).
- **master** - The default development branch. Whenever you create a Git repository, a branch named "master" is created, and becomes the active branch. In most cases, this contains the local development, though that is purely by convention and is not required.
   - Although the current default development branch on GitHub is the `master` branch, [GitHub is working on changing it to a neutral term](https://www.bbc.co.uk/news/technology-53050955) such as `main`.
- **merge** - Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line. A merge can be done through a pull request via the GitHub.com web interface if there are no conflicting changes, or can always be done via the command line.
- **merge conflict** - A difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.
- **open source** - Open source software is software that can be freely used, modified, and shared (in both modified and unmodified form) by anyone. Today the concept of "open source" is often extended beyond software, to represent a philosophy of collaboration in which working materials are made available online for anyone to fork, modify, discuss, and contribute to.
- **project board** - Boards within GitHub that are made up of issues, pull requests, and notes that are categorized as cards in columns.
- **pull request** - Pull requests are proposed changes to a repository submitted by a user and accepted or rejected by a repository's collaborators. Like issues, pull requests each have their own discussion forum.
- **README** - A text file containing information about the files in a repository that is typically the first file a visitor to your repository will see. A README file, along with a repository license, contribution guidelines, and a code of conduct, helps you share expectations and manage contributions to your project.
- **remote** - This is the version of a repository or branch that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be synced.
- **repository** - A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.
- **review** - Reviews allow others with access to your repository to comment on the changes proposed in pull requests, approve the changes, or request further changes before the pull request is merged.
- **star** - A bookmark or display of appreciation for a repository. Stars are a manual way to rank the popularity of projects.
- **watch** - You can watch a repository or issue to receive notifications when updates are made to an issue or pull request.

