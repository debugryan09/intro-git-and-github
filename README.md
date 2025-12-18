# Project Plan: Introduction to Git and GitHub

This project is designed for a 2-hour high school session. Students will build a "Mini Personal Portfolio" while learning the fundamentals of version control.

## Overview
- **Prerequisites:** GitHub account, Git installed, basic HTML/CSS/JS knowledge.
- **Workflow:** Students fork the teacher's repository and work on their individual copies.
- **Timeframe:** 120 Minutes.

---

## Lesson 1: The Local Foundation (30 Minutes)
**Directory:** `lesson-1-basics/`
**Concepts:** `git status`, `git add`, `git commit`, `git log`

1.  **Task:** Create an `index.html` file in the `lesson-1-basics/` folder.
2.  **Activity:**
    *   Write a basic HTML structure with an `<h1>` containing your name and a `<p>` with a short bio.
    *   Use `git status` to see the untracked file.
    *   Use `git add index.html` to stage the changes.
    *   Use `git commit -m "Initial commit: Add bio page"` to save the snapshot.
    *   Use `git log` to view the commit history.

## Lesson 2: Branching Out (30 Minutes)
**Directory:** `lesson-2-branches/`
**Concepts:** `git branch`, `git checkout` (or `git switch`), `git merge`

1.  **Task:** Add styling to your portfolio without messing up the main version.
2.  **Activity:**
    *   Create a new branch: `git branch feature-style`.
    *   Switch to it: `git checkout feature-style`.
    *   Create a `style.css` file and link it in `index.html`. Add some colors and fonts.
    *   Commit the CSS changes on this branch.
    *   Switch back to `main` and notice the CSS file "disappears."
    *   Merge the changes: `git merge feature-style`.

## Lesson 3: Connecting to the Cloud (30 Minutes)
**Directory:** `lesson-3-remotes/`
**Concepts:** `git push`, `git fetch`, `git pull`

1.  **Task:** Sync local work with the GitHub fork.
2.  **Activity:**
    *   Use `git push origin main` to send local commits to GitHub.
    *   **Simulate a remote change:** Go to the GitHub website, edit the `README.md` file directly in the browser, and commit it.
    *   Back in the terminal, use `git fetch` to see that changes exist.
    *   Use `git pull` to bring those remote changes into the local environment.

## Lesson 4: The Pull Request (30 Minutes)
**Directory:** `lesson-4-pull-requests/`
**Concepts:** Feature branching, GitHub UI, Pull Requests

1.  **Task:** Add an interactive JavaScript feature and "submit" it for review.
2.  **Activity:**
    *   Create a new branch: `git checkout -b feature-js`.
    *   In the `lesson-4-pull-requests/` directory, create a `script.js` that adds an alert or a dark-mode toggle to the portfolio.
    *   Add and commit the changes.
    *   Push the new branch to GitHub: `git push origin feature-js`.
    *   **GitHub UI:** Navigate to the repository on GitHub and click the "Compare & pull request" button.
    *   Write a clear description of the changes and submit the Pull Request to your own `main` branch.

---

## Commands Summary Reference
*   `git status`: Check what has changed.
*   `git add <file>`: Prepare changes for a commit.
*   `git commit -m "message"`: Save a snapshot of staged changes.
*   `git log`: View history of commits.
*   `git branch <name>`: Create a new branch.
*   `git checkout <name>`: Switch to a branch.
*   `git push origin <branch>`: Send local commits to GitHub.
*   `git pull`: Download and merge changes from GitHub.