# Ex-01 DevOps_Exploring-Git-Commands-through-Collaborative-Coding

## Aim:
The aim of this experiment is to familiarize participants with essential Git concepts and commands, enabling them to effectively use Git for version control and collaboration.
## Theory:
Git is a distributed version control system (VCS) that helps developers track changes in their codebase, collaborate with others, and manage different versions of their projects efficiently. It was created by Linus Torvalds in 2005 to address the shortcomings of existing version control systems.
Unlike traditional centralised VCS, where all changes are stored on a central server, Git follows a distributed model. Each developer has a complete copy of the repository on their local machine, including the entire history of the project. This decentralisation offers numerous advantages, such as offline work, faster operations, and enhanced collaboration.
Git is a widely used version control system that allows developers to collaborate on projects, track changes, and manage codebase history efficiently. This experiment aims to provide a hands-on introduction to Git and explore various fundamental Git commands. Participants will learn how to set up a Git repository, commit changes, manage branches, and collaborate with others using Git.


## **Key Concepts**
- **Repository**: A collection of files, folders, and their historical versions, including project history, branches, and commits.
- **Commit**: A snapshot of changes made to files in the repository, identified by a unique SHA-1 hash and a descriptive message.
- **Branch**: A separate line of development within a repository for working on features or bug fixes independently.
- **Merge**: Combines changes from one branch into another.
- **Pull Request**: Facilitates code review and collaboration on Git hosting platforms before merging changes.
- **Remote Repository**: A copy of the Git repository stored on a server, enabling collaboration among developers. Examples include GitHub, GitLab, and Bitbucket.

---

## **Basic Git Commands**
- `git init`: Initializes a new Git repository in the current directory.
- `git clone`: Creates a copy of a remote repository on your local machine.
- `git add`: Stages changes for commit, preparing them for the next commit.
- `git commit`: Creates a new commit with a descriptive message for the staged changes.
- `git status`: Shows the current status of the working directory, including tracked and untracked files.
- `git log`: Displays a list of commits in the repository with details like commit messages, authors, and timestamps.
- `git branch`: Lists, creates, or deletes branches within the repository.
- `git checkout`: Switches between branches, commits, or tags to navigate the repository's history.
- `git merge`: Combines changes from different branches into the current branch.
- `git pull`: Fetches and merges changes from a remote repository into the current branch.
- `git push`: Sends local commits to a remote repository.

---

## **Materials Required**
- Computer with [Git installed](https://git-scm.com/downloads)
- Command-line interface (Terminal, Command Prompt, or Git Bash)

# Experiment Steps

---

## **Step 1: Cloning a Repository**
- Sign in to your GitHub account.
- Find a repository to clone (you can use a repository of your own or any public repository).
- Click the "Code" button and copy the repository URL.
- Open your terminal or command prompt.
- Navigate to the directory where you want to clone the repository.
- Clone the repository using the URL copied from GitHub.

---

## **Step 2: Making Changes and Creating a Branch**
- Navigate into the cloned repository.
- Create a new text file named `example.txt` using a text editor.
- Add some content to the `example.txt` file.
- Save the file and return to the command line.
- Check the status of the repository.
- Stage and commit the changes with a descriptive message.
- Create a new branch named `feature`.
- Switch to the `feature` branch.

---

## **Step 3: Pushing Changes to GitHub**
- Add the repository URL to your Git configuration.
- Push the `feature` branch to GitHub.
- Verify on GitHub that the new branch `feature` is available.

---

## **Step 4: Collaborating through Pull Requests**
- Create a pull request on GitHub:
  - Navigate to the repository on GitHub.
  - Click on "Pull Requests" and then "New Pull Request."
  - Choose the base branch (usually `main` or `master`) and the compare branch (`feature`).
  - Review the changes and click "Create Pull Request."
- Review and merge the pull request:
  - Add a title and description for the pull request.
  - Assign reviewers if needed.
  - Once approved, merge the pull request into the base branch.


## **Step 5: Syncing Changes**
- After merging the pull request, update your local repository with the latest changes from the base branch.

## Conclusion:
Through this experiment, participants gained a foundational understanding of Git's essential commands and concepts. They learned how to set up a Git repository, manage changes, explore commit history, create and merge branches, and collaborate with remote repositories. This knowledge equips them with the skills needed to effectively use Git for version control and collaborative software development.
