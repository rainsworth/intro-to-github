# A friendly introduction to version control, git and GitHub

## Version control

**Version control** is a way of tracking changes to a document or collection of documents, and helps to solve one of the main challenges in working with many people on a single project. Your collaborators may be spread around the world or working in the same room; they may be working simultaneously or asynchronously. No matter how your team is organised, the work of many contributors needs to be wrangled into a single project. Version control manages this process: it stores a history of changes and who made them, allowing you to revert or go back to earlier versions of those documents, and understand how contributions by different contributors have changed the project over time. 

You may have used word processing software that has a “changes,” “history” or “revisions” feature, which also allows you to see and revisit any changes to the document (such as Microsoft Word’s [Track Changes](https://support.office.com/en-us/article/Track-changes-in-Word-197ba630-0f5f-4a8e-9a77-3712475e806a), Google Docs’ [version history](https://support.google.com/docs/answer/190843?hl=en), or LibreOffice’s [Recording and Displaying Changes](https://help.libreoffice.org/Common/Recording_and_Displaying_Changes)): this is also a form of version control. 

When we code, write text, or create any kind of content using computers, we end up with a collection of files in a folder or directory, also known as a **repository** or “repo”.

![repo image](https://raw.githubusercontent.com/mozillascience/study-group-onboarding/master/images/gh04.png)

Even if you’re working independently, you’re probably going to make a lot of changes to your content or code as you go. For example, you will change some wording or functionality and leave others untouched - you will also make mistakes or change your mind while you experiment with new ideas!

![repo changes image](https://raw.githubusercontent.com/mozillascience/study-group-onboarding/master/images/gh05.png)

As you make changes, you might make multiple copies of your files to preserve a version that's working while you try to improve it or add functionality, but keeping track of all these versions and the differences between them becomes difficult. It also seems ridiculous to have multiple nearly-identical versions of the same document. (We want to avoid [this situation](http://phdcomics.com/comics/archive.php?comicid=1531).) If you work with others, maybe you email the different versions back and forth, renaming the file each time (`code.py`, `code_rachael-comments.py`, `code-v2_rachael-comments.py`, and so on...). Whether you work alone or with others, if this situation looks familiar then you could benefit from version control. 

![filenames image](https://raw.githubusercontent.com/mozillascience/study-group-onboarding/master/images/gh06.png)

Version control systems start with a base version of the document and then records changes made each step of the way. Like a time machine, it can take you back to the moment your document was created, or to any other point in time when you or a collaborator saved changes to that document. With version control, you don’t save multiple copies of the document, you just save the timeline of changes of the document.

![timeline image](https://raw.githubusercontent.com/mozillascience/study-group-onboarding/master/images/gh07.png)

So what’s on the timeline? Each record of these changes is called a **commit**, which stores information on what changes were made, when and by whom. The timeline of the document is therefore a series of commits. Each commit should have an associated commit message, with a brief description of what changes were made and why.

![commit image](https://raw.githubusercontent.com/mozillascience/study-group-onboarding/master/images/gh08.png)

When we share and work on projects with collaborators, managing the changes, or commits that multiple collaborators working in different places at different times make to a single set of documents becomes very, very important. 

![collab image](https://raw.githubusercontent.com/mozillascience/study-group-onboarding/master/images/gh09.png)

And when we’re working with multiple collaborators, everybody needs to know and understand what commits are being incorporated into the repository and why, so good communication becomes very, very important. The great news is that there’s a piece of version control software to help us both manage and communicate with our collaborators about commits to our project, and that software is called **Git**.


## Git


## GitHub


## Attribution

The content in this file has been adapted from:
* Mozilla Science Lab's [Study Group Orientation](https://mozillascience.github.io/study-group-orientation/), Licensed [MPL 2.0](https://www.mozilla.org/en-US/MPL/2.0/)
* Software Carpentry's [Version Control with Git](http://swcarpentry.github.io/git-novice/), Licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
