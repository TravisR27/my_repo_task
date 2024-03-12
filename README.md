# my_repo_task

Practical Task 1
Follow these steps:
● Create an empty folder called git_task_project.
● Open your terminal or command prompt and then change directory (cd) to
your newly created folder.
● Enter the git init command to Initialise your new repository.
● Enter the git status command and make a note of what you see. You
should have a clean working directory.
● Create a new file in the git_task_project folder called helloWorld.py and
write a program that prints out the message “Hello World!”
● Run the git status command again. You should now see that your
helloWorld.py file is untracked.
● Enter the git add command followed by helloWorld.py to start tracking
your new file.
● Once again, run the git status command. You should now see that your
helloWorld.py file is tracked and staged to be committed
● Now that it is tracked, let us change the file helloWorld.py. Change the
message printed out by the program to “Git is awesome!”
● Run git status again. You should see that helloWorld.py appears under a
section called “Changes not staged for commit”. This means that the file is
tracked but has been modified and not yet staged.
● Take a screenshot of this change and title it: git_modified.pdf or
git_modified.jpeg. Include it as part of your submission.
● To stage your file, simply run git add again.
● If you run git status again you should see that it is once again staged for
your next commit.
● You can now commit your changes by running the git commit -m
command. Remember to enter a suitable commit message after the -m
switch.
● Running the git status command should show a clean working directory
once again.
● Now run the git log command. You should see your commit listed.
● Take a screenshot of the output and add it to the task folder. Name the
submitted image file: git_log.pdf or git_log.jpeg


Practical Task 2
Follow these steps:
● Open your terminal or command prompt and change directory (cd) to the
folder git_task_project created above.
● Create a new branch called issue-1 using the git branch command.
● Switch to your new issue-1 branch by using the git checkout command.
● Once you are on the issue-1 branch, change the helloWorld.py file. Modify
your program to accept input from the user and then print out the inputted
data.
● Add and commit your changes.
● Check out the master branch and use the git merge command to merge
branches.
● Take a screenshot of the output after running the git merge command and
upload it to the task folder.
● Name the submitted image file: git_merge.pdf or git_merge.jpeg.


Practical Task 3
● Pick any one of your GitHub repos.
● Create 2 issues for things you think could be improved. Ideas for
improvements include making new methods, adding constants, renaming
variables and functions, or adding comments.
● For each issue:
○ Create a branch with a meaningful name.
○ Implement the changes required by the issue.
○ Commit and push your work.
○ Create a PR for your changes.
○ Merge in the PR and close the issue.
● In a text file called repo.txt, paste the link to your repo. Add the file to this
task’s folder
