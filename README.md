# Tailor-connect

1.  **Initialize a new Git repository in your project folder:**
    ```bash
    git init
    ```
    *(This creates a hidden `.git` directory to track changes.)*

2.  **Add your project files to the staging area:**
    ```bash
    git add .
    # Or to add a specific file:
    # git add your-file.txt
    ```
    *(The staging area prepares changes to be included in the next commit.)*

3.  **Commit your staged changes (create a snapshot of your project's state):**
    ```bash
    git commit -m "Initial commit of project files"
    # The message in quotes should be a concise description of the changes.
    ```

4.  **Connect your local repository to a remote GitHub repository:**
    *(First, create an empty repository on GitHub and copy its URL.)*
    ```bash
    git remote add origin [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    # 'origin' is a conventional name for your primary remote repository.
    ```

5.  **Push your local commits to the remote GitHub repository:**
    ```bash
    git push -u origin main
    # '-u origin main' sets up the 'main' branch on 'origin' as the default upstream branch.
    # Subsequent pushes can just be 'git push'. (Note: 'main' is now preferred over 'master'.)
    ```
