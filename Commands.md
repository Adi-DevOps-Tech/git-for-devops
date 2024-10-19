### Git Command Notes
#### Initialization
- **`git init`**
  - Initializes a new Git repository.
  - **Example:**
    ```bash
    git init my-project
    ```

#### Status and Tracking
- **`git status`**
  - Displays the current status of the repository, including staged, unstaged, and untracked files.
  - **Example:**
    ```bash
    git status
    ```

#### Staging Changes
- **`git add <filename>`**
  - Stages a specific file for commit.
  - **Example:**
    ```bash
    git add index.html
    ```
- **`git add .`**
  - Stages all changes in the current directory for commit.
  - **Example:**
    ```bash
    git add .
    ```

#### Committing Changes
- **`git commit -m "<message>"`**
  - Commits the staged changes with a descriptive message.
  - **Example:**
    ```bash
    git commit -m "Add initial HTML structure"
    ```

#### Viewing History
- **`git log`**
  - Shows the commit history, including commit IDs, authors, and messages.
  - **Example:**
    ```bash
    git log
    ```

#### Branch Management
- **`git branch`**
  - Lists all branches in the repository.
  - **Example:**
    ```bash
    git branch
    ```
- **`git branch -b <branch_name>`**
  - Creates a new branch and switches to it.
  - **Example:**
    ```bash
    git branch -b feature-x
    ```
- **`git checkout <branch_name>`**
  - Switches to an existing branch.
  - **Example:**
    ```bash
    git checkout main
    ```
- **`git checkout -b <new_branch_name>`**
  - Creates a new branch and switches to it.
  - **Example:**
    ```bash
    git checkout -b feature-y
    ```

#### Restoring Files
- **`git restore <filename>`**
  - Restores a file to its last committed state, discarding any changes made since then.
  - **Example:**
    ```bash
    git restore index.html
    ```

### Tips
- Regularly use `git status` to keep track of changes before committing.
- Provide clear and descriptive commit messages to maintain a helpful project history.
