# How to Forcefully Upload All Files to GitHub

These instructions will guide you through initializing a new Git repository, adding all your project files, and forcefully pushing them to a remote repository on GitHub.

**Warning:** Force pushing (`git push --force`) will overwrite the history of the remote branch. This is a destructive operation and should be used with caution. If you are collaborating with others, this can cause serious problems. Only proceed if you are certain this is what you want to do, for example, when setting up a repository for the first time or fixing a major mistake in your own branch.

## Steps

1.  **Navigate to your project's root directory**

    Open your terminal or command prompt and change to the root directory of your project.
    ```bash
    cd c:\Users\Asus\AI-Code-Reviewer
    ```

2.  **Initialize a new Git repository**

    If you haven't already, initialize a Git repository in your project folder.
    ```bash
    git init
    ```

3.  **Add a remote repository**

    Link your local repository to a remote repository on GitHub. Replace `<your-github-repo-url>` with the actual URL of your GitHub repository.
    ```bash
    git remote add origin <your-github-repo-url>
    ```
    *Example: `git remote add origin https://github.com/your-username/your-repo-name.git`*

4.  **Add all files to the staging area**

    This command stages all files and directories in the current directory for the first commit.
    ```bash
    git add .
    ```

5.  **Commit the files**

    Commit the staged files to your local repository with a message.
    ```bash
    git commit -m "Initial commit"
    ```

6.  **Forcefully push to GitHub**

    This command will push your commit to the `main` branch of your remote repository, overwriting any history that was there. If your default branch is `master`, use `master` instead of `main`.
    ```bash
    git push --force origin main
    ```

After these steps, all your local files will be on your GitHub repository. For subsequent changes, you can use a regular `git push origin main` without the `--force` flag.
