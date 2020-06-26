# GitHub Interface Tour and Jargon Busting

## Interface Tour

1. GitHub home page: https://github.com/ (sign up or log in!)
2. GitHub dashboard: https://github.com/ (logged in)
   - Your personal dashboard is the main hub of your activity on GitHub.
   - The dashboard might be confusing until we cover the topics related to repositories (such as issues, pull requests, etc.).
   - Therefore, we'll briefly see the dashboard and then come back to it after touring the user profile and a repository interfaces).
   - Click the icon in the top right corner and select "Your profile".
3. GitHub profile: https://github.com/rainsworth
   - This is the page that shows information about a user's activity on GitHub.
   - User profile information such as name, description, links and organisations can be seen in the left sidebar.
   - The Overview tab displays the user's pinned repositories and contribution activity on GitHub.
   - The Repositories tab displays a list of the user's repositories.
   - The Projects and Packages tabs are beyond the scope of this session, but you can click the "Learn More" buttons to learn more about them.
   - Click back to the Repositories tab and go to the `intro-to-github` repository.
4. GitHub repository: https://github.com/rainsworth/intro-to-github
   - A repository (or "repo") is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.
   - At the very top you will see the user and repository name displayed as `username/repository-name`.
   - Underneath and to the right you will see buttons that say "Watch", "Star" and "Fork".
      - You can click "Watch" to watch a repository or issue to receive notifications when updates are made to an issue or pull request.
      - You can click "Star" to bookmark or display appreciation for a repository. 
      - You can click "Fork" to make a personal copy of another user's repository that lives on your account. Forks allow you to freely make changes to a project without affecting the original upstream repository. You can also open a pull request in the upstream repository and keep your fork synced with the latest changes since both repositories are still connected.
   - Underneath that you will see a set of tabs labelled Code, Issues, Pull requests, etc. which we will navigate through now:
      - Code
         - This is the tab where you can view and interact directly with the contents of the repository.
         - In the right sidebar you will see information "About" the repository (such as a description, tagged topics, links to the README and license, release, package and environment information).
         - The repository file system is displayed (which contains the files associated with the project such as code, data, text, images, etc.).
            - Click through to a few of the files to preview them.
         - The README is automatically rendered underneath the file system. The README is a text file containing information about the repository that is typically the first file a visitor to your repository will see.
         - Above the file system is a set of buttons:
            - Branch (click to view the different branches)
            - Go to file (click to easily search for a file within the repository)
            - Add file (click to add a new file to the repository)
            - Clone (click to clone the repository to your local workspace, open with the [GitHub Desktop](https://desktop.github.com/) app or download the .zip file)
      - Issues
         - Click on the [Example Issue](https://github.com/rainsworth/intro-to-github/issues/18).
         - Issues are suggested improvements, tasks or questions related to the repository.
         - Issues can be created by anyone (for public repositories), and are moderated by repository collaborators. 
         - Each issue contains its own discussion thread. 
         - You can also categorise an issue with labels, assign it to someone and add to a project management board in the right sidebar.
      - Pull requests
         - Pull requests are proposed changes to a repository submitted by a user and accepted or rejected by a repository's collaborators. 
         - Like issues, pull requests each have their own discussion forum which you can see in the Conversation tab.
         - You can also categorise a pull request with labels, assign it to someone, assign a reviewer, add to a project management board and link to open issues in the right sidebar.
         - The Commits tab displays the record of the specific changes commited along with who made them and when.
         - The Checks tab is beyond the scope of this session. Checks are external processes, such as continuous integration builds, which run for each commit you make in a repository. For more information, see "[About status checks](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-status-checks)."
         - The Files changed tab displays all the files that have been changed within the pull request and their associated "diffs" which are the difference in changes between two commits, or saved changes. The diff will visually describe what was added or removed from a file since its last commit.
      - Actions are beyond the scope of this session, but you can learn more about [Getting started with GitHub Actions here](https://help.github.com/en/actions/getting-started-with-github-actions)
      - Projects
         - Projects are boards within GitHub that are made up of issues, pull requests, and notes that are categorized as cards in columns.
         - They help you visualise your project workflow and enable project management.
         - Click on [Introduction to GitHub](https://github.com/rainsworth/intro-to-github/projects/1).
         - This project has a basic kanban template which tracks my tasks with To do, In progress, and Done columns.
         - You can create cards and move them around to help visualise any bottlenecks in your development.
         - You can also click on "Add cards" to the right of the project board to create cards from issues and pull requests.
      - Wiki
         - Wikis provide a place in your repository to lay out the roadmap of your project, show the current status, and document software better, together.
      - Security 
         - The Security tab is where you set up security features for your repository.
      - Insights
         - The Insights tab allows you to explore the activity within your repository such as an overview of issues and pull requests, who has contributed to the repository, traffic to the repository, the network graph (timeline of the most recent commits to this repository and its network ordered by most recently pushed to), who has forked the repository and more.
         - Click around the different items in the left sidebar to explore.
      - Settings
         - The Settings tab allows you to manage the settings of your repository, such as the repository name, enabling features, setting up GitHub pages (turing your repo into a website), deleting the repository, managing notifications and more.
         - Click around the different items in the left sidebar to explore.


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
- **Dashboard** - Your personal dashboard is the main hub of your activity on GitHub. From your personal dashboard, you can keep track of issues and pull requests you're following or working on, navigate to your top repositories and team pages, and learn about recent activity in repositories you're watching or participating in. You can also discover new repositories, which are recommended based on users you're following and repositories you have starred. To only view activity for a specific organization, visit your organization's dashboard. For more information, see "[About your personal dashboard](https://help.github.com/en/articles/about-your-personal-dashboard)" or "[About your organization dashboard](https://help.github.com/en/articles/about-your-organization-dashboard)."
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
- **profile** - The page that shows information about a user's activity on GitHub.
- **project board** - Boards within GitHub that are made up of issues, pull requests, and notes that are categorized as cards in columns.
- **pull request** - Pull requests are proposed changes to a repository submitted by a user and accepted or rejected by a repository's collaborators. Like issues, pull requests each have their own discussion forum.
- **README** - A text file containing information about the files in a repository that is typically the first file a visitor to your repository will see. A README file, along with a repository license, contribution guidelines, and a code of conduct, helps you share expectations and manage contributions to your project.
- **remote** - This is the version of a repository or branch that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be synced.
- **repository** - A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.
- **review** - Reviews allow others with access to your repository to comment on the changes proposed in pull requests, approve the changes, or request further changes before the pull request is merged.
- **star** - A bookmark or display of appreciation for a repository. Stars are a manual way to rank the popularity of projects.
- **watch** - You can watch a repository or issue to receive notifications when updates are made to an issue or pull request.
- **Wiki** - A section for hosting wiki style documentation on a GitHub repository.
