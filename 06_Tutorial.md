# Tutorial to set up a GitHub repository/project

Outline:
   - Hello World tutorial: https://guides.github.com/activities/hello-world/
   - Contribute to @OpenDataManchester's Pick N Mix repository: https://github.com/OpenDataManchester/training-and-resources
   - Create a personal website using GitHub Pages tutorial: https://guides.github.com/features/pages/


## Hello World

We will first work through the [GitHub Guides Hello Wolrd](https://guides.github.com/activities/hello-world/) tutorial. The guide teaches you how to 
- Create and use a **repository**
- Start and manage a new **branch**
- Make changes to a file and **push** them to GitHub as **commits**
- Open and **merge** a **pull request**



## Contributing to another user's repository

Next, I will demonstrate how to make a contribution to another user's repository where I don't have write access. In this example, I will add my resources to Open Data Manchester's [Training and Resources](https://github.com/OpenDataManchester/training-and-resources) repository where they share all the resources related to their Pick N Mix series. We will learn how to 
- **Fork** someone else's repository
- Make changes to a file and **push** them to GitHub as **commits**
- Open a **pull request** to contribute them back to the original project 

Tutorial:
1. Go to Open Data Manchester's `training-and-resources` repository: https://github.com/OpenDataManchester/training-and-resources
2. I want to make changes to a project that I don’t have write access to. I therefore need to **fork** the repository. A **fork** is a personal copy of another user's repository that lives on your account. Forks allow you to freely make changes to a project without affecting the original repository. That is, I can safely play around with the repository without breaking someone else's project. In the top right corner, click the `Fork` button.
3. Open the `Pick-N-Mix` folder and explore the contents to learn more about the repository and see how best to contribute. Based on the existing structure, I can see that I should add a sub-directory with a README linking to the resources for my Intro to GitHub Pick N Mix session. 
3. Since I will not be changing any of the existing files, I will click on the `Add file` button and select `Create new file`.
4. We now see the editor where we will create our new file. Following the convention of the repository, I will create `readme.md` in a folder called `Intro to GitHub`. To do this, I type  
   ```
   Intro to GitHub/readme.md
   ```  
   into the box where is asks you to `Name your file..`. The backslash is what allows you to create a new folder with the file inside.
6. I can then copy and paste my list of resources into the README:
   ```
   Resources and links for Pick N Mix 9: an introduction to Github, with Dr Rachael Ainsworth, 30th June 2020.
   
   [Materials/resources for session](https://github.com/rainsworth/intro-to-github)
   
   [Rachael on Twitter](https://twitter.com/rachaelevelyn)
   
   [HER+Data MCR on Twitter](https://twitter.com/herplusdatamcr)
   
   [HER+Data MCR on Meetup](https://www.meetup.com/HER-Data-MCR)
   ```
7. Once I've added my changes I can scroll to the bottom to add a meaningful commit message 
   ```
   create intro to github readme
   ``` 
   and click `Commit new file`.
8. I can now see a new notification on my **fork** of the repository which reads `This branch is 1 commit ahead of OpenDataManchester:master.` with links to `Pull request` and `Compare`. 
9. I am now on a page titled "Comparing changes" where I can choose two branches (or forks) to see what’s changed or to start a new pull request. You can see the list of commits and the files changed. If there are no conflicts with the original repository, it will say ` Able to merge. These branches can be automatically merged.` When I am ready to contribute my changes back to the original repository, click `Create pull request`. 
10. A text box will open prompting me to leave a comment about my pull request. It is good practice to rename with a more meaningful title and describe to the repository owners what changes I am proposing and why to help them assess my contributions. I will leave the following comment: 
   ```
   This pull request adds the list of resources for Pick N Mix 9: an introduction to Github.
   ``` 
11. Click `Create pull request` to request that the repository owners pull your contributions into their project. Congratulations, you've contributed to an open source project! :tada:

