# Lesson 2: Branching Out

In this lesson, you will learn how to use **branches** to work on new features without changing your main project until you are ready.

## Concepts
* `git branch <name>`: Create a new branch.
* `git checkout <name>`: Switch from one branch to another.
* `git merge <name>`: Combine the changes from one branch into your current branch.

## Instructions

1. **Open your terminal** and navigate to this directory: `lesson-2-branches/`.
2. **Create a new branch**: Run `git branch feature-style`. This creates a copy of your current state to work on styling.
3. **Switch to your branch**: Run `git checkout feature-style`.
4. **Create a CSS file**: Create a file named `style.css` in this directory. Add some CSS to change the background color or font of your portfolio.
5. **Link the CSS**: Update your `index.html` (from Lesson 1) to link to this new `style.css` file.
6. **Commit your changes**: 
    * Run `git add .`
    * Run `git commit -m "Add styling on a new branch"`
7. **The Magic Moment**: 
    * Switch back to the main branch: `git checkout main`.
    * Look at your folder. Where did `style.css` go? (Git hides it because it only exists on the `feature-style` branch!)
8. **Merge the work**: Now that you're happy with the style, bring it into the main project:
    * Run `git merge feature-style`.
    * Check your folder again—the CSS file is back!

## Success Criteria
* You successfully switched between branches.
* You merged the `feature-style` branch into `main`.
* Your directory now contains both `index.html` and `style.css`.