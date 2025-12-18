# Lesson 4: The Pull Request

In this final lesson, you will learn the "social" side of Git: the **Pull Request (PR)**. This is how professional developers propose changes to a project and get their code reviewed by teammates.

## Concepts
* **Feature Branching**: Creating a specific branch for a single task or "feature".
* **Pull Request**: A request to merge your branch into another branch (usually `main`), providing a space for discussion and review.
* **GitHub UI**: Using the website to manage the integration of your code.

## Instructions

1. **Open your terminal** and navigate to this directory: `lesson-4-pull-requests/`.
2. **Create a feature branch**: Run `git checkout -b feature-js`. (The `-b` flag creates the branch and switches to it in one step!)
3. **Add Interactivity**: Create a file named `script.js` in this directory. Add a simple JavaScript alert or a button that changes the background color. 
   * *Example:* `console.log("Portfolio Loaded!");`
4. **Link the script**: Update your `index.html` to include `<script src="script.js"></script>` before the closing `</body>` tag.
5. **Commit your changes**:
    * Run `git add .`
    * Run `git commit -m "Add JavaScript feature"`
6. **Push the branch**: Run `git push origin feature-js`.
7. **Create the PR on GitHub**:
    * Go to your repository on GitHub.com.
    * You should see a yellow bar that says "feature-js had recent pushes". Click **Compare & pull request**.
    * Write a brief description of what your JavaScript does.
    * Click **Create pull request**.
8. **Merge the PR**: Since this is your own project, you can review it yourself. Click the green **Merge pull request** button, then **Confirm merge**.

## Success Criteria
* You created a new branch and pushed it to GitHub.
* You opened a Pull Request on the GitHub website.
* You successfully merged that PR into your `main` branch.
* Your `main` branch on GitHub now contains the `script.js` file.