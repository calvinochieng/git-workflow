# git-workflow
These are step by step to help you learn the git command from creating local repo to upoading it to hosted repo
##Guide
1. Create new repo in github by adding new repository
2. Clone this repo to local machine ``git clone <link to clone from>``
3. Now you can add any file or just work on the project folder

##Working your Project
You can create a file lets say index.html, do any changes to your exsiting files
So for this to be availbale online you have to to do these commands
```
git status 
git add .
git commit -m 'Message on the changes you've added'
git push
```
Let me explain thse command one by one

1. `git status` this command as it says, is to help you see the status of your project that is any file(s) that has been added or any file that has been changed
2. `git add .` this the command for adding the files to the staging area just before commit for them to be tracked
3. `git commit -m'message'` this make sure the files you've changed or added have been added to the local repository with a message for the change
4. `git push` this is the final command that will you push your code to online repository you've setup

