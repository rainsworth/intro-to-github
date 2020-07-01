# GitHub for collaboration and best practices

At the heart of GitHub is collaboration. The [GitHub flow](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/github-flow) was developed for collaboration on projects. To make it work for teams regardless of their size or technical expertise, GitHub made sure each step in their workflow can be completed within the web-based interface.

There are two main types of [collaborative development models](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-collaborative-development-models): 
1. In the *fork and pull model*, anyone can fork an existing repository and push changes to their personal fork. You do not need permission to the source repository to push to a user-owned fork. This model is popular with open source projects as it reduces the amount of friction for new contributors and allows people to work independently without upfront coordination.
2. In the *shared repository model*, collaborators are granted push access to a single shared repository and topic branches are created when changes need to be made. This model is more prevalent with small teams and organizations collaborating on private projects.

Below we'll cover:
- [Project Collaborators](#project-collaborators)
- [Issues and Pull requests](#issues-and-pull-requests)
- [Community Profile](#community-profile)
- [Projects](#projects)
- [Wikis](#wikis)


## Project Collaborators

You can invite users to become collaborators to your personal repository, which grants them read/write access to the project (shared repository model). 

- [Inviting collaborators to a personal repository](https://help.github.com/en/github/setting-up-and-managing-your-github-user-account/inviting-collaborators-to-a-personal-repository)
- [Collaborator access on a repository owned by a user account](https://help.github.com/en/github/setting-up-and-managing-your-github-user-account/permission-levels-for-a-user-account-repository#collaborator-access-on-a-repository-owned-by-a-user-account)


## Issues and Pull requests

Issues and pull requests facilitate [discussions on GitHub](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-conversations-on-github#discussions-on-github). Issues are useful for discussing specific details of a project such as bug reports and planned improvements. Pull requests allow you to comment directly on proposed changes. 

- [Collaborating with issues and pull requests](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests)
- [Managing your work with issues](https://help.github.com/en/github/managing-your-work-on-github/managing-your-work-with-issues)
- [Reviewing pull requests](https://lab.github.com/githubtraining/reviewing-pull-requests)


## Community Profile

GitHub has created a Community Profile checklist to help make sure your project meets the recommended community standards to help people use and contribute to your project. You can read more [About community profiles for public repositories](https://help.github.com/en/github/building-a-strong-community/about-community-profiles-for-public-repositories), [Starting an Open Source Project](https://opensource.guide/starting-a-project/) and [Building Welcoming Communities](https://opensource.guide/building-community/). You can also take the [Community starter kit](https://lab.github.com/githubtraining/community-starter-kit) course in the GitHub Learning Lab to learn about the informal standards the community has adopted to make it easier to find and contribute to projects.

You can find the Community Profile checklist via the `Insights` tab and then select `Community` in the left sidebar. It checks to see if a project includes recommended community health files, such as
- [ ] Description
- [ ] README
- [ ] Code of Conduct
- [ ] Contributing guidelines
- [ ] License
- [ ] Issue templates
- [ ] Pull Request templates

I have listed [definitions](https://help.github.com/en/github/getting-started-with-github/github-glossary) and resources below to help you get started on these files:
- **Description**: Add an optional short description about the repository which will be displayed in the right sidebar of the `Code` tab.
- **README**: A text file containing information about the files in a repository that is typically the first file a visitor to your repository will see. A README file, along with a repository license, contribution guidelines, and a code of conduct, helps you share expectations and manage contributions to your project.
   - [Documenting your projects on GitHub](https://guides.github.com/features/wikis/)
   - [About READMEs](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes)
   - [Make a README](https://www.makeareadme.com/)
   - [A good README template](https://github.com/PurpleBooth/a-good-readme-template)
   - [README Checklist](https://github.com/ddbeck/readme-checklist/blob/master/checklist.md)
   - [Awesome READMEs](https://github.com/matiassingers/awesome-readme)
- **Code of Conduct**: A document that defines standards for how to engage in a community.
   - [Adding a code of conduct to your project](https://help.github.com/en/github/building-a-strong-community/adding-a-code-of-conduct-to-your-project)
   - [Your Code of Conduct](https://opensource.guide/code-of-conduct/)
- **Contributing guidelines**:  A document explaining how people should contribute to your project.
   - [Setting guidelines for repository contributors](https://help.github.com/en/github/building-a-strong-community/setting-guidelines-for-repository-contributors)
   - [How to Build a CONTRIBUTING.md](https://mozillascience.github.io/working-open-workshop/contributing/)
   - [Contributing Guides: A Template](https://github.com/nayafia/contributing-template/)
- **License**: A document that you can include with your project to let people know what they can and can't do with your source code.
   - [Adding a license to a repository](https://help.github.com/en/github/building-a-strong-community/adding-a-license-to-a-repository)
   - [Licensing a repository](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/licensing-a-repository)
   - [How to choose a license for your GitHub repository](https://choosealicense.com/)
   - [The Legal Side of Open Source](https://opensource.guide/legal/)
- **Issue and Pull Request templates**: With issue and pull request templates, you can customize and standardize the information you'd like contributors to include when they open issues and pull requests in your repository.
   - [Using templates to encourage useful issues and pull requests](https://help.github.com/en/github/building-a-strong-community/using-templates-to-encourage-useful-issues-and-pull-requests)


## Projects

[Project boards](https://help.github.com/en/github/managing-your-work-on-github/about-project-boards) on GitHub help you organize and prioritize your work. They are made up of issues, pull requests, and notes that are categorized as cards in columns of your choosing. You can create project boards for specific feature work, comprehensive roadmaps, or even release checklists. With project boards, you have the flexibility to create customized workflows that suit your needs.

- [Managing project boards](https://help.github.com/en/github/managing-your-work-on-github/managing-project-boards)
- [Tracking the progress of your work with project boards](https://help.github.com/en/github/managing-your-work-on-github/tracking-the-progress-of-your-work-with-project-boards)


## Wikis

Every GitHub repository comes equipped with a section for hosting documentation, called a [wiki](https://help.github.com/en/github/building-a-strong-community/about-wikis). You can use your repository's wiki to share long-form content about your project, such as how to use it, how you designed it, or its core principles. A README file quickly tells what your project can do, while you can use a wiki to provide additional documentation.

- [Documenting your project with wikis](https://help.github.com/en/github/building-a-strong-community/documenting-your-project-with-wikis)
- [Documenting your projects on GitHub](https://guides.github.com/features/wikis/)

---

Next: [More Resources](07_MoreResources.md)
