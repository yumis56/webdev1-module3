# Git Commands Manual for Students

This manual will guide you through the basic Git commands necessary to successfully complete your assignment.

## Essential Git Commands

### 1. git clone

Clone a repository to your local machine.

**Usage:**
```bash
git clone <repository-url>
```

### 2. git status

Check the status of your working directory.

**Usage:**
```bash
git status
```

### 3. git branch

Create, list, rename, and delete branches.

**Usage:**
```bash
# Create a new branch
git branch <branch-name>

# List all branches
git branch -a

# Rename a branch
git branch -m <old-branch-name> <new-branch-name>

# Delete a branch
git branch -d <branch-name>
```

### 4. git checkout

Switch between different branches and commits.

**Usage:**
```bash
# Switch to an existing branch
git checkout <branch-name>

# Create a new branch and switch to it
git checkout -b <new-branch-name>
```

### 5. git add

Add changes in your working directory to your index (the 'staging area').

**Usage:**
```bash
# Add a specific file
git add <file>

# Add all changes
git add .
```

### 6. git commit

Capture a snapshot of the project's currently staged changes.

**Usage:**
```bash
# Commit with a message
git commit -m "<message>"
```

### 7. git pull

Fetch changes from the remote repository and merge them into your current branch.

**Usage:**
```bash
# Pull changes from the remote repository
git pull
```

### 8. git push

Send your committed changes to the remote repository for others to access and use.

**Usage:**
```bash
# Push changes to the remote repository
git push origin <branch-name>
```

### 9. git log

Show the commit history.

**Usage:**
```bash
git log
```

## Git Commands in Action

Here's a comprehensive example of how you might use these commands together:

1. First, clone the repository:
    ```bash
    git clone https://github.com/user/repo.git
    ```

2. Navigate into the directory of the cloned repository.
3. Check the status of your Git repository:
    ```bash
    git status
    ```

4. Create and switch to a new branch called "new-feature":
    ```bash
    git checkout -b new-feature
    ```

5. Make some changes to your project files.
6. Check the status of your Git repository again to see what has changed:
    ```bash
    git status
    ```

7. Add your changes to the staging area:
    ```bash
    git add .
    ```

8. Commit your changes with a meaningful message:
    ```bash
    git commit -m "Add new feature"
    ```

9. Push your changes to the remote repository:
    ```bash
    git push origin new-feature
    ```

10. You can now open a Pull Request on GitHub to merge your changes into the main code base.
11. Finally, check the commit history of your repository to see your new commit:
    ```bash
    git log
    ```
