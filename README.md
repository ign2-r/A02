# Git and GitHub Tutorial

## Part 1: Using WebStorm

### Step 1: Download and Install Git

1. If you haven't already, download and install Git from the [official Git website](https://git-scm.com/downloads). Follow the installation instructions for your operating system.

### Step 2: Download and Install WebStorm

1. Go to the [JetBrains website](https://www.jetbrains.com/webstorm/download/) to download WebStorm.
2. You will have to apply for a student license to be able to successfully download it.
3. Follow the installation instructions for your operating system.

### Step 3: Configure Git in WebStorm

1. Open WebStorm.
2. Go to `File > Settings` (or `WebStorm > Preferences` on macOS).
3. In the Settings dialog, navigate to `Version Control > Git`.
4. Ensure that the path to the Git executable is correctly set. If not, click on the `...` button and locate the Git executable on your system.
5. Click `Apply` and then `OK` to save the changes.

### Step 4: Clone a GitHub Repository

1. Open WebStorm.
2. Select `VCS > Git > Clone` from the menu.
3. Enter the URL of the GitHub repository you want to clone.
4. Choose a directory where you want to save the local copy of the repository.
5. Click `Clone` to clone the repository.

### Step 5: Make Changes and Commit

1. Make changes to the files in your project.
2. In WebStorm, open the `Version Control` tool window by selecting `View > Tool Windows > Version Control` from the menu.
3. You will see the changed files listed under the `Local Changes` tab.
4. Select the files you want to commit.
5. Enter a commit message describing the changes.
6. Click `Commit` to commit the changes to your local repository.

### Step 6: Push Changes to GitHub

1. After committing your changes, select `VCS > Git > Push` from the menu.
2. If prompted, enter your GitHub credentials.
3. Click `Push` to push your changes to the remote repository on GitHub.

### Step 7: Pull Changes from GitHub

1. To pull changes from the remote repository on GitHub, select `VCS > Git > Pull` from the menu.
2. WebStorm will fetch the latest changes from the remote repository and merge them into your local repository.

## Part 2: Glossary

- **Branch**: A parallel version of a repository, allowing you to work on different features or fixes independently.
- **Clone**: To create a local copy of a repository from a remote source.
- **Commit**: To save changes to the local repository with a descriptive message.
- **Fetch**: To retrieve changes from a remote repository without merging them into the local branch.
- **GIT**: A distributed version control system for tracking changes in source code during software development.
- **GitHub**: A web-based platform for hosting and collaborating on Git repositories.
- **Merge**: To integrate changes from one branch into another.
- **Merge Conflict**: Occurs when Git is unable to automatically resolve differences between two branches.
- **Push**: To send committed changes from the local repository to a remote repository.
- **Pull**: To retrieve and merge changes from a remote repository into the local repository.
- **Remote**: A version of the repository that is hosted on a server, typically on platforms like GitHub.
- **Repository**: A storage location where your project's files and revision history are stored.

### References

- [JetBrains Website](https://www.jetbrains.com/)
- [Git Documentation](https://git-scm.com/doc)
- [GitHub Guides](https://guides.github.com/)
