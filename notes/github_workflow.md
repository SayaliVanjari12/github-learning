# GitHub Workflow Notes

## Branch

### What is it?
A branch is a separate line of development in a repository. It allows us to work on a feature without directly changing the main branch.

### Why is it useful?
It keeps different changes separate and makes it safer to work on new features or fixes.

### Where is it used?
Usually, a developer creates a feature branch from the latest main branch, makes changes and commits them there, and later creates a Pull Request.

---

## Pull Request

### What is it?
A Pull Request is a request to merge the changes from one branch into another branch.

### Why is it useful?
It gives other developers a chance to review the changes before they are added to the main branch.

### Where is it used?
After completing work on a feature branch, we push the branch to GitHub and create a Pull Request, usually targeting main.

---

## Merge

### What is it?
Merge combines the changes from one branch into another branch.

### Why is it useful?
It allows completed and reviewed work to become part of the main codebase.

### Where is it used?
After a Pull Request is reviewed and approved, the feature branch can be merged into main.

---

## Code Review

### What is it?
Code review is the process of checking someone else's code and giving feedback on it.

### Why is it useful?
It helps find bugs, improve the code, and make sure the changes follow the project's requirements.

### Where is it used?
Code review usually happens on a Pull Request before the changes are merged into main.

---

## GitHub Issue

### What is it?
A GitHub Issue is used to record a task, problem, feature request, or piece of work that needs to be done.

### Why is it useful?
It helps the team keep track of what needs to be worked on and provides context for the changes.

### Where is it used?
A developer can create an Issue for a feature or bug and then create a branch and Pull Request to work on that Issue.

---

## Repository

### What is it?
A repository is a project managed by Git. It contains the project files as well as their version history.

### Why is it useful?
It keeps the code and its history in one place and allows developers to work together on the project.

### Where is it used?
A project is stored in a repository, and developers clone it, create branches, make commits, and push their changes to it.

---

## Fork

### What is it?
A fork is a copy of someone else's GitHub repository under your own GitHub account.

### Why is it useful?
It allows you to make changes to a repository when you don't have direct permission to push to the original repository.

### Where is it used?
Forks are commonly used when contributing to open-source projects. You make changes in your fork and then create a Pull Request to the original repository.