# Lesson 1: The Local Foundation

In this lesson, you will learn how to initialize a project, track changes, and save snapshots of your work using Git.

## Concepts
* `git status`: See what files Git is watching.
* `git add`: Stage your changes (tell Git which files to include in the next snapshot).
* `git commit`: Save a snapshot of your staged changes with a descriptive message.
* `git log`: View the history of your commits.

## Instructions

1. **Open your terminal** and navigate to this directory: `lesson-1-basics/`.
2. **Create a file** named `index.html`.
3. **Add some content** to `index.html`. It should include:
    * An `<h1>` with your name.
    * A `<p>` with a short bio about yourself.
4. **Check the status**: Run `git status`. You should see `index.html` listed as an "untracked file" in red.
5. **Stage the file**: Run `git add index.html`.
6. **Check the status again**: Run `git status`. The file should now be green, meaning it is "staged" and ready to be committed.
7. **Commit your work**: Run `git commit -m "Initial commit: Add bio page"`.
8. **View your history**: Run `git log`. You should see your commit along with the author name, date, and your message.

## Success Criteria
* You have an `index.html` file in this directory.
* When you run `git status`, it says "nothing to commit, working tree clean".
* When you run `git log`, you see at least one commit entry.