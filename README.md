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
6.  **Pull Request (PR)**: Open a pull request from your branch to the original project's main branch to propose your changes