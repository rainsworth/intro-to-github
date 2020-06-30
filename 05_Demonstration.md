# Using GitHub Demonstration

Table of Contents:
- [Hello World](#hello-world)
- [Contributing to another user's repository](#contributing-to-another-users-repository)
- [Creating a personal website using GitHub Pages](#creating-a-personal-website-using-github-pages)


## Hello World

We will first work through the [GitHub Guides Hello World](https://guides.github.com/activities/hello-world/) tutorial. The guide teaches you how to 
- Create and use a **repository**
- Start and manage a new **branch**
- Make changes to a file and **push** them to GitHub as **commits**
- Open and **merge** a **pull request**

Demonstration (steps are from the [GitHub Guides Hello World](https://guides.github.com/activities/hello-world/) tutorial, see the guide for full context, screenshots, and further instructions):
1. To create a new **repository**, click the `+` in the upper right corner next to your avatar or identicon and then select `New repository`.
2. Name your **repository** `hello-world`, write a short description, check the box to `Initialize this repository with a README`, and then click `Create repository`.
3. We can now view our new **repository**. By default, the repository has one **branch** named `master` which is considered to be the definitive branch (although [GitHub is working on changing it to a neutral term](https://www.bbc.co.uk/news/technology-53050955) such as `main`). We use branches to experiment and make edits before committing them to the default branch. To create a new branch, click the drop down at the top of the file list that says `branch: master`. Type a branch name, `readme-edits`, into the new branch text box and select `Create branch: readme-edits`.
4. We are now viewing the `readme-edits` **branch** of our **repository** which for now looks just like our default branch - but not for long as we are going to make changes to the README. Click the `README.md` file.
5. Click the pencil icon in the upper right corner of the file view to edit. In the editor, add a short blurb such as
   ```
   I am currently demonstrating how to create and use a **repository**, start and manage a new **branch**, and make changes to a file and **push** them to GitHub as **commits**.
   ```
   Once I've added my changes I can scroll to the bottom to add a meaningful **commit** message that describes the changes and then click the `Commit changes` button. These changes will be made to just the README file on the `readme-edits` **branch**, so now this branch contains content that’s different from the default branch.
6. Once I preview and am happy with my changes on the `readme-edits` **branch**, it is time to open a **pull request** to **merge** these changes into the default branch. Click on the `Pull Request` tab at the top of the repo, then from the Pull Request page, click the green `New pull request` button. (Alternatively, you can take advantage of GitHub's more recent features. There should be a notification highlighted in yellow that indicates `readme-edits had recent pushes` with a green `Compare & pull request` button which you can click to skip step 7.)
7. I am now on a page titled "Comparing changes". In the `compare` box, select the **branch** you made, `readme-edits`, to compare with `base: master` (the original). Pay careful attention to the direction of the arrow when choosing how to compare branches.
8. The Comparing changes page now displays the list of **commits** and the files changed. If there are no conflicts with the original **branch**, it will say ` Able to merge. These branches can be automatically merged.` Look over the changes in the diffs and make sure they’re what you want to submit. When you’re satisfied that these are the changes you want to submit, click the big green `Create pull request` button. 
9. A text box will open prompting me to leave a comment about my **pull request**. Give your pull request a title and write a brief description of your changes. I will leave the following comment:
   ```
   This pull request adds information about the demonstration to the README.
   ```
   When you’re done with your message, click `Create pull request`!
10. In this final step, it’s time to bring the changes together and **merge** your `readme-edits` branch into the `master` branch. Click the green `Merge pull request` button to merge the changes into `master` and click `Confirm merge`. (You can then go ahead and delete the branch, since its changes have been incorporated, with the `Delete branch` button.) Congratulations, you've opened and merged your first pull request! :tada:


## Contributing to another user's repository

Next, I will demonstrate how to make a contribution to another user's repository where I don't have write access. In this example, I will add my resources to Open Data Manchester's [Training and Resources](https://github.com/OpenDataManchester/training-and-resources) repository where they share all the resources related to their Pick N Mix series. We will learn how to 
- **Fork** someone else's repository
- Make changes to a file and push them to GitHub as **commits**
- Open a **pull request** to contribute them back to the original project 

Demonstration:
1. Go to Open Data Manchester's `training-and-resources` repository: https://github.com/OpenDataManchester/training-and-resources
2. I want to make changes to a project that I don’t have write access to. I therefore need to **fork** the repository. A **fork** is a personal copy of another user's repository that lives on your account. Forks allow you to freely make changes to a project without affecting the original repository. That is, I can safely play around with the repository without breaking someone else's project. In the top right corner, click the `Fork` button.
3. Open the `Pick-N-Mix` folder and explore the contents to learn more about the repository and see how best to contribute. Based on the existing structure, I can see that I should add a sub-directory with a README linking to the resources for my Intro to GitHub Pick N Mix session. 
3. Since I will not be changing any of the existing files, I will click on the `Add file` button and select `Create new file`.
4. We now see the editor where we will create our new file. Following the convention of the repository, I will create `readme.md` in a folder called `Intro to GitHub`. To do this, I type  
   ```
   Intro to GitHub/readme.md
   ```  
   into the box where is asks you to `Name your file..`. The backslash is what allows you to create a new folder with the file inside.
6. I can then copy and paste my list of resources in Markdown syntax into the README:
   ```
   Resources and links for Pick N Mix 9: an introduction to Github, with Dr Rachael Ainsworth, 30th June 2020.
   
   [Materials/resources for session](https://github.com/rainsworth/intro-to-github)
   
   [Rachael on Twitter](https://twitter.com/rachaelevelyn)
   
   [HER+Data MCR on Twitter](https://twitter.com/herplusdatamcr)
   
   [HER+Data MCR on Meetup](https://www.meetup.com/HER-Data-MCR)
   ```
7. Once I've added my changes I can scroll to the bottom to add a meaningful **commit** message 
   ```
   create intro to github readme
   ``` 
   and click `Commit new file`.
8. I can now see a new notification on my **fork** of the repository which reads `This branch is 1 commit ahead of OpenDataManchester:master.` with links to `Pull request` and `Compare`. Click `Pull request`. 
9. I am now on a page titled "Comparing changes" where I can choose two branches (or forks) to see what’s changed or to start a new **pull request**. You can see the list of **commits** and the files changed. If there are no conflicts with the original repository, it will say ` Able to merge. These branches can be automatically merged.` When I am ready to submit my contributions back to the original repository for consideration, click `Create pull request`. 
10. A text box will open prompting me to leave a comment about my **pull request**. It is good practice to rename with a more meaningful title and describe to the repository owners what changes I am proposing and why to help them assess my contributions. I will leave the following comment: 
   ```
   This pull request adds the list of resources for Pick N Mix 9: an introduction to Github.
   ```
11. Click `Create pull request` to request that the repository owners pull your contributions into their project. Congratulations, you've contributed to an open source project! :tada:


## Creating a personal website using GitHub Pages

For a beginners guide to creating a personal website using GitHub Pages, check out the [GitHub Guides Getting Started with GitHub Pages](https://guides.github.com/features/pages/) tutorial and the [GitHub Pages](https://lab.github.com/githubtraining/github-pages) course on GitHub Learning Lab. If you want to practice more of the concepts that we covered in the previous demonstration, you can follow the steps outlined below.

1. Identify what information/sections/tabs/pages you want to include on your website (e.g. an About page, an events page, a list of projects, a blog, contact info, etc.).
2. Choose a theme (e.g. from [http://jekyllthemes.org/](http://jekyllthemes.org/)) that you like that will best present that information.
3. Go to your chosen theme's GitHub **repository** (for example I used the [Moon](https://github.com/TaylanTatli/Moon) theme for my GitHub website that you can view here: https://rainsworth.github.io
4. **Fork** the theme **repository**. This copies the contents of the theme to your account so that you can edit and use while maintaining credit to the theme authors.
5. Go to the `Settings` tab to update the repository name to `username.github.io` (replacing "username" with your GitHub username) and enable GitHub Pages by selecting a permitted branch (usually `master` or `gh-pages`) as a source for your webpage. GitHub will then indicate where your site is published in a green notification box (in this case, at https://username.github.io where "username" is your GitHub username).
6. Return to the `Code` tab and edit the `_config.yml` file to point to your repository, change the title and any other user information.
7. Edit the `README` to include information about the website or project repository (read more about `README` files [here](https://help.github.com/articles/about-readmes/)).
8. **Make your changes**! In this case, add or change elements to the website as you see fit (you can add relevant information to the About page, add your projects to the Projects page, add blog posts to Posts, etc.). 
9. Once you're happy with your changes, submit a **pull request**. 
10. **Merge** the **pull request** and check out your website! :tada:

---

Next: [GitHub for collaboration and best practices](06_Collaboration.md)
