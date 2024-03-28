# User System Guide

For a new User, these are the tools to be downloaded.

  1. Gitbash version 2.44.0.exe (downloaded)  
  2. Maven version 3.9.6(downloaded)
  3. IntelliJ version 2023.3.6 (downloaded)
  4. Tried setting the path for JAVA_HOME, M2_HOME, MVN_HOME on "Environment variable" in the "System Variables".
  4. Coordinator invited us on the github and then we generated the ssh key.
  5. Coordinator added our public keys.
  6. Cloned Coordinator's repository via HTTPS on our editor Intellij.
   Now we are ready to push or pull branches in the github repository.

Various Git Commands to get used to

  git init: Initializes a new Git repository in the current directory.
  git clone <repository-url>: Clones a repository from a remote URL to your local machine.
  git add <file> or git add .: Adds files to the staging area, preparing them to be committed.
  git commit -m "commit message": Commits the staged changes to the local repository with a descriptive message.
  git status: Shows the current status of the repository, including modified, staged, and untracked files.
  git diff: Shows the differences between the working directory and the staging area.
  git diff --staged or git diff --cached: Shows the differences between the staging area and the last commit.
  git log: Displays a chronological list of commits in the repository.
  git branch: Lists all branches in the repository.
  git branch <branch-name>: Creates a new branch with the specified name.
  git checkout <branch-name>: Switches to the specified branch.
  git merge <branch-name>: Merges the specified branch into the current branch.
  git remote: Lists all remote repositories associated with the local repository.
  git remote add <name> <url>: Adds a new remote repository.
  git push <remote-name> <branch-name>: Pushes commits from the local repository to a remote repository.
  git pull <remote-name> <branch-name>: Fetches changes from a remote repository and merges them into the current branch.
  git fetch: Downloads objects and refs from another repository.
  git reset <file>: Unstages the specified file, but keeps the changes in the working directory.
  git reset --hard: Resets the staging area and working directory to the state of the last commit.
  git rm <file>: Removes the specified file from both the working directory and the staging area.

  Added Dilshad as a Collaborator through git invitation