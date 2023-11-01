Question 1 / List three major version control for software engineering.
Local Version Control System.
Centralized Version Control System.
Distributed Version Control System.

Question 2 / What are the main advantages to using Git in your software development, and how is it useful for game developers.
Each developer receives their own local repository with a complete history of commits, rather than a functioning copy. Git is quick when you have a complete local history since it eliminates the need for a network connection when creating commits, viewing older versions of files, and diffing between changes.

Question 3 / Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge
A Git repository is a central storage location for managing and tracking changes in files and directories.
The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content.
The git push command is used to upload local repository content to a remote repository.
"working copy" for git is a directory full of files with a . git subdirectory. It's the same as a local git repository.
Merging is Git's method of reassembling a forked history. The git merge command combines the independent lines of development created by git branch into a single branch.

Question 4 / If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.
Write the smallest amount of code possible to solve a problem, Committing code in small batches decreases the likelihood of integration conflicts.
Using branches, software development teams can make changes without affecting the main codeline. The running history of changes are tracked in a branch, and when the code is ready, it's merged into the main branch.
Descriptive commit messages are as important as a change itself. Write descriptive commit messages starting with a verb in present tense in imperative mood to indicate the purpose of each commit in a clear and concise manner.
Requesting feedback from others is an excellent way to ensure code quality. Code reviews are an effective method to identify whether a proposal solves a problem in the most effective way possible.

Question 5 / Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.
gitk - gitk is a graphical history viewer.
git-gui - git gui focuses on allowing users to make changes to their repository by making new commits, amending existing ones, creating branches, performing local merges, and fetching/pushing to remote repositories.
Vimdiff3 - Vimdiff3 by each file gets its own window. The differences between the files are highlighted. This is a nice way to inspect changes and to move changes from one version to another version of the same file.
KDiff3 - Kdiff3 is an open source file comparison tool supported on Windows, OSX, and various flavors of Unix/Linux. It provides a easy to understand GUI for comparing files, directories, and merging files.
XXdiff - xxdiff is a graphical browser for viewing the differences between two or three files, or between two directories, and can be used to produce a merged version.

Quesion 6 / In a merged source code file, how does Git let you know there is a conflict?
For simple text files, Git uses an approach known as the longest common subsequence algorithm to perform merges and to detect merge conflicts. In its simplest form, Git find the longest set of lines in common between your changed file and the common ancestor.

Question 7 / What are the steps you can take to resolve Git conflicts?
Step 1: The easiest way to resolve a conflicted file is to open it and make any necessary changes.
Step 2: After editing the file, we can use the git add a command to stage the new merged content.
Step 3: The final step is to create a new commit with the help of the git commit command.
Step 4: Git will create a new merge commit to finalize the merge.

Question 8 / What does git revert do, and how can you use it?
The git revert command is a forward-moving undo operation that offers a safe method of undoing changes Instead of deleting.
Open your repo in VS Code.
From the sidebar select Source Control.
Navigate to the COMMITS section.
Right-click on the commit you want to revert.
Select the Revert Commit option.

Question 9 / What does git reset do, and how can you use it? 
git reset is a powerful command that is used to undo local changes to the state of a Git repo.
Step 1: Find the previous commit:
Step 2: Move the repository back to that step

Question 10 / What is the difference between git revert and git reset?
git revert as a tool for undoing committed changes, while git reset HEAD is for undoing uncommitted changes.

Question 11 / True or False: It is okay to commit broken code to the main branch.
False (Just don't. you can just dont)

Question 12 / True or False: A commit should only include files that are related to the change you are committing to the repo.
True

small change

Question 13 / Describe what is DevOps, how is it useful for game developers?Development and operations teams are no longer separate spaces in a DevOps model. These two teams may merge into a single team in which the engineers work across the entire application lifecycle, from development and testing to deployment and operations.

Question 14 / List what tools can be used with DevOps. Give a brief description of each one. (at least 3)
Git DevOps tools - Git DevOps tools is easy to implement as it is compatible with most protocols including HTTP, SSH, and FTP. It offers the best advantage for non-linear shared-repository development projects, unlike most other centralized version control tools. This makes it a good deal for mission-critical software. 
Maven - Maven is one of the important DevOps tools for building projects. Unlike the ANT build system, Apache Maven is more than just an automation build framework. It is also designed to manage reporting, documentation, distribution, releases, and dependencies processes. Written in Java language, Maven can build and manage projects written in Java or C#, Ruby, Scala, and other languages using project object model (POM) plugins.
Jenkins - Jenkins is an integration DevOps tool. For continuous integration (CI), Jenkins stands out as it is designed for both internal and plugin extensions. Jenkins is an open-source Java-based automation CI server that is supported by multiple operating systems including Windows, macOS, and other Unix OSs. Jenkins can also be deployed on cloud-based platforms. 

Question 15 / What is CI/CD and how can it be used to automate the game development process/
CI/CD is a method of delivering apps to customers on a regular basis by incorporating automation into the stages of app development. Continuous integration, continuous delivery, and continuous deployment are the three main concepts associated with CI/CD. CI/CD is a solution to the problems that new code integration can cause for development and operations teams (also known as "integration hell").
