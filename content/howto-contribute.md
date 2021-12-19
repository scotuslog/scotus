---
Title: How To Contribute
Description: 
Author: Editor
Date: 2021-12-15 10:31:03
Template: index
Hidden: true
---
# How To Submit Your Writing and Research

The process to submit stories and content to this website is quite simple, but for non-technical people, it can be kind of confusing.

The website is very simple technology. There is no database or admin interface to manage the content and stories. Everything is a text file and managed via Github.com.

To submit content, that's done via Github.com.

Git is a version control system used in most software development projects. In this context, Git is being used to manage not just source code, but content. At the end of the day, a text file about Clarence Thomas' life is practically no different than application source code.

* Researcher Early Life through College - Need people to dig into the lives of each justice from birth to graduating from college. If there was a birth announcement in a local paper, can we get a scan of it? Are there any recent interviews with people who discuss the justice's formative years and refer to anyone by name who can be researched or interviewed? What about photos of the justice when they're a kid?
    * John Roberts (Unassigned)
    * Clarence Thomas (Unassigned)
    * Brett Kavanaugh (Unassigned)
    * Neil Gorsuch (Unassigned)
    * Samual Alito (Unassigned)
    * Amy Comey Barrett (Unassigned)

The Git workflow used for this website is as follows.
  1. You create a branch of this Git repo.
  2. Make your changes in your branch.
  3. Commit your changes to your Git branch.
  4. Create a Git pull request using your Git branch.
  5. Submit your Git pull request to be merged into the main branch and made live.

There are two options for making this all happen. 

## The Easy Way to Contribute Content

## The Advanced Way To Contribute Content
If you are comfortable with Git, or want don't mind learning, the advanced method of contributing content can work well.

The main advantage to this method is that you can write content in any editor you want, as opposed to using Github.com.

### Download Github Desktop
If you're a techno wizard, you can use the git command line to do all of this, but if you're a git guru, you don't need read any of these instructions.

For everyone else, [download](https://desktop.github.com/ "Download Github Desktop") and install the Github Desktop Client

[![Download Github Desktop](%assets_url%/git-desktop-icon.svg)](https://desktop.github.com/ "Download Github Desktop")

Open the Github Desktop client and clone this repo scotuslog/scotus.

![Clone Git Repo](%assets_url%/git-contribute-clone.png)

### Create Git Branch
You will make your changes in your own branch of this Git repo.

![Create Git Branch](%assets_url%/git-contribute-branch.png)

You can name your branch whatever you want, but it's good practice to make it meaningful.

![Name Git Branch](%assets_url%/git-contribute-name.png)

### Write
The Git repo has been cloned and you have your branch. Now make whatever changes you want to make to one of the markdown files in the content directory. The files are located in the directory where you cloned the Git repo.

What's markdown? You can learn more about markdown [here](https://www.markdownguide.org).

### Save Your Work
You made your changes and they look great, so it's time to commit what you wrote to your new Git branch.

Using Github Desktop, you should see something like this.

![Commit to Your Git Branch](%assets_url%/git-contribute-commit.png)

With changes committed to your branch, now you have to publish your new branch to Git. When you initially create a branch locally, it only exists on your local computer, you have to specifically publish your branch. 

But don't worry, you're not publishing to the website when you commit to your branch. It's just committing changes to your Git branch, which will become a pull request.

### Create a Pull Request
Committing to your Git branch "saves" your changes, but it doesn't publish your changes to the public website. To do that, you need to create a pull request.

What's a pull request? When you submit a pull request, you're asking the owner of the Git repo to accept your changes. Whether your changes will be accepted is based on whether or not your submission followed the style guide.

> If you're really interested in what pull requests are, you can read about pull > request on GitHub [here](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests).

You can use Github Desktop to create a new pull request.

![Create Git Pull Request](%assets_url%/git-contribute-create-pr.png)