# Git-Practice-Mohammad-Aljabali

## Git vs. GitHub

- **Git**
  - A distributed version control *software* installed locally.
  - Tracks the history and changes of your code on your machine.
- **GitHub**
  - A cloud-based *service* that hosts Git repositories.
  - Enhances collaboration with features like Pull Requests, code reviews, and issue tracking.

---

## `git fetch` vs. `git pull`

- **`git fetch`**:
  - Downloads remote changes but does **not** merge them.
  - Allows you to review changes before integrating them into your working branch.
- **`git pull`**:
  - Downloads remote changes *and* automatically tries to merge them.
  - Essentially a combination of `git fetch` followed by `git merge`.

---

## The `.gitignore` File

The `.gitignore` file specifies which files or directories Git should intentionally ignore. This keeps the repository clean by excluding unnecessary or sensitive files.

- **Common files to ignore**:
  - Dependency folders: `node_modules/`
  - Environment variables: `.env`
  - Build outputs: `build/`, `dist/`
  - Log files: `*.log`
  - Compiled code: `*.class`, `*.o`

---

## Open-Source Contribution Workflow

1.  **Fork**: Create your own copy of the project repository on GitHub.
2.  **Clone**: Download your forked repository to your local machine.
    ```sh
    git clone <your-fork-url>
    ```
3.  **Branch**: Create a new branch to contain your changes.
    ```sh
    git checkout -b <new-feature-branch-name>
    ```
4.  **Commit**: Make your changes and commit them with a clear message.
    ```sh
    git commit -m "feat: Add new feature"
    ```
5.  **Push**: Push your new branch and its commits to your forked repository.
    ```sh
    git push origin <new-feature-branch-name>
    ```
6.  **Pull Request (PR)**: Open a pull request from your branch to the original project's main branch to propose your changes.

### Part 2: Practical Git & GitHub Task

#### 1. Repository Initialization and Cloning

-   **Objective**: Create a GitHub repository named `Git-Practice-Mohammad-Aljabali`, initialize it with a README, and clone it locally.
-   **Status**: The repository was created on GitHub and successfully cloned to the local machine.

#### 2. Python Script Creation and Push

-   **Objective**: Create a Python script that prints 'Hello GitHub!' and push it to the `main` branch.
-   **Status**:
    -   `hello.py` was created with the specified content.
    -   The script was added, committed, and pushed to the `main` branch.

#### 3. Feature Branch, New File, and Push

-   **Objective**: Create a new branch named `feature/info`, add an `info.txt` file with personal details, and push the new branch.
-   **Status**:
    -   The `feature/info` branch was created and checked out.
    -   `info.txt` was created with personal information.
    -   The new file was added, committed, and the `feature/info` branch was pushed to the remote repository.

#### 4. Merge `feature/info` via Pull Request

-   **Objective**: Merge the `feature/info` branch into the `main` branch using a Pull Request on GitHub.
-   **Status**: A Pull Request was created, and the `feature/info` branch was successfully merged into `main`. The local `main` branch was updated to reflect these changes.

#### 5. Fix Branch, README Update, and Merge

-   **Objective**: Create a `fix/readme` branch, update the `README.md` with a task summary, and merge it.
-   **Status**:
    -   The `fix/readme` branch was created and checked out.
    -   `README.md` was updated with the task summary.
    -   The changes were committed, and the `fix/readme` branch was pushed.
    -   A Pull Request was created, and the branch was successfully merged into `main`. The local `main` branch was updated accordingly.

#### 6. Optional (Bonus): `.gitignore` File

-   **Objective**: Add and configure a `.gitignore` file to ignore Python cache files.
-   **Status**:
    -   A `.gitignore` file was created.
    -   `__pycache__/` and `*.pyc` were added to the file.
    -   The `.gitignore` file was added, committed, and pushed to the `main` branch.

