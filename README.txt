Exercise Part 2 - Git

Notice that there is now a .git directory in git-practice — you'll see it if you run the ls -a command.

Create a new file called README.txt and run git status. What output do you get?

Use the git add README.txt command to add the new file to the staging area. Run git status again — how has the output changed?

Now that you're satisfied with the changes that you've staged, commit them using git commit -m "...". Give the commit an appropriate message — remember, it should be short but descriptive.

Create a directory called src and add a couple of files to it.

Use the add command, but add the src directory instead of the individual files. Use the git status command — see how both files have been staged? Go ahead and commit the addition of these new files to the repo.

Make a change to one of the files, and run git diff to look at all of the unstaged changes to our repo. What do you see?
