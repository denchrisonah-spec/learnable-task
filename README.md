ASSIGNMENT: VERSION CONTROL AND GIT CONCEPTS

1. Introduction to Version Control

Version control is a system used to track and manage changes made to files over time. It allows developers to keep a history of their work, making it possible to revisit earlier versions, compare changes, and collaborate with others efficiently.


2. Difference Between Git and GitHub

Git
Git is a software tool installed on a computer that tracks changes in files. It works locally and does not require an internet connection. Developers use Git to manage versions of their code.

GitHub
GitHub is an online platform that hosts Git repositories. It allows developers to store their projects in the cloud and collaborate with others. It also provides additional features such as issue tracking and pull requests.


3. GitHub Alternatives

There are several alternatives to GitHub that provide similar services:

1. GitLab – A complete DevOps platform with built-in CI/CD tools.
2. Bitbucket – Integrates well with Atlassian tools like Jira.
3. SourceForge – An older but still relevant platform for hosting open-source projects.

4. Difference Between git fetch and git pull

Both commands are used to update a local repository with changes from a remote repository, but they work differently:

git fetch
The `git fetch` command downloads changes from the remote repository without applying them to the local working files. It allows the user to review updates before merging them.

git pull
The `git pull` command downloads changes and immediately applies them to the local repository. It combines fetching and merging into one step.


5. Git Rebase (Simple Explanation)
Git rebase is used to move or reapply changes from one branch onto another. It helps keep a clean and linear project history by placing your work on top of the latest version of another branch.

Command:
git rebase main

This command reapplies your current branch changes on top of the main branch.

6. Git Cherry-pick (Simple Explanation)
Git cherry-pick is used to select a specific commit from one branch and apply it to another branch. It is useful when you only need a particular change instead of merging an entire branch.

Command:
git cherry-pick <commit-hash>

This command applies the selected commit to your current branch.


