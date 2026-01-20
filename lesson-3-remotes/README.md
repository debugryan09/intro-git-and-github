# Lesson 3: Connecting to the Cloud

In this lesson, you will learn how to synchronize your local work with a remote server (GitHub) so you can back up your code and collaborate with others.

## Concepts
* `git push`: Send your local commits to the remote repository on GitHub.
* `git fetch`: Check the remote repository for changes without downloading them into your files.
* `git pull`: Download changes from the remote repository and merge them into your local files.

## Instructions

1. **Open your terminal** and navigate to this directory: `lesson-3-remotes/`.
2. **Push your work**: Run `git push origin main`. This sends all the commits you made in Lesson 1 and 2 up to your GitHub profile.
3. **Verify on GitHub**: Open your browser, go to your repository on GitHub, and verify that your files and commit history are visible there.
4. **Simulate a Remote Change**:
    * On the GitHub website, click on the `README.md` file in the root of your project.
    * Click the pencil icon to edit.
    * Add a line at the bottom: `Edited this on GitHub!`
    * Scroll down and click "Commit changes".
5. **Fetch the changes**: Back in your terminal, run `git fetch`. This tells your local Git that something changed on the server.
6. **Pull the changes**: Run `git pull`. 
7. **Verify**: Open your local `README.md` file. You should now see the line you wrote on the website!

## Success Criteria
* Your code is visible on your GitHub profile.
* You successfully "pulled" a change from the website down to your computer.
* Your local repository is in sync with your remote repository.


  Edited on Github
