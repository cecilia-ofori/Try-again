
 1 .Git was created by Linus Torvalds, the same person who developed the Linux kernel.


The essence of Git lies in its ability to manage and track changes in source code (or other types of files) across time and collaboration,

2. Git is a version control system (VCS) used to track changes in your code or files over time. It is a tool you run locally on your computer, managing your project’s history, commits, branches, merges, etc.
Key Functions:

Track changes to files.

Allow branching and merging for collaboration.

Manage project history.

Work both online and offline (locally).

git init:Initialize a new Git repository.

git commit:Record changes.

git push: Upload changes to a remote repository.


GitHub is a cloud-based platform that hosts Git repositories. It is the most widely used platform for storing and collaborating on Git repositories. It adds a lot of features for collaboration, such as pull requests, issues, actions, and more.

Key Features:

Remote Git hosting: You store your Git repositories online.

Collaboration tools: Issues, pull requests, comments, and more to help teams work together.

Public and private repositories: You can make repositories public or private.

Community and open-source: GitHub is a massive hub for open-source projects, and it supports social coding with stars, forks, and followers.

GitHub Actions: CI/CD pipelines to automate tasks like testing and deploying code.

Code reviews: You can easily collaborate on code changes through pull requests.

3.Subversion (SVN)


 SVN is a centralized version control system (CVCS), meaning there is one central repository, and developers check out copies of the project from it to work on.

 Mercurial (Hg)

 Mercurial is another distributed version control system similar to Git. It is known for being easy to use and having a simpler learning curve than Git.


 Perforce (Helix Core)


Perforce, also known as Helix Core, is a centralized version control system designed to handle large-scale software development with large codebases (often used in game development, enterprise, and media industries).

4. git status :

 It shows the current state of your working directory and staging area

5.
Commit

A commit in Git is like taking a snapshot of your project at a certain point in time. It's a way to save your changes and keep track of them in your project's history



    Git log command is used to display the commit history of a Git repository.
    
     It shows a list of commits, including details such as the commit hash, author, date, and commit message.
    

    Example in image


    8 The command git add is used in Git to stage changes for the next commit. When you make changes to files in your working directory (such as editing, adding new files, or deleting files), those changes are not automatically tracked by Git until you stage them using git add.


    Staging area in Git is where you prepare your changes before committing them to the local repository. It allows you to carefully select which changes you want to include in your next commit.

    