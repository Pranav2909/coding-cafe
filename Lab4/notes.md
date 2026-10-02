1.) Basically, --global is used to save one's Email-Id and name throughout the system for all users for all the repositories created using git. If --global isn't used then the name and Email-Id is only valid for the current working repository and not for all repositories.

2.) In ls only the folders and files are visible but hidden folders starting with a dot(.) are invisble using ls -a displays all of the files, folders and hidden folders as well.

3.) Git has no limitations it can track all of the files and folders, the only catch is that it can't track hidden folders which start with dot(.).

4.) Nothing actually disappeared actually .gitignore was the extra file that appeared on the list, intially in the question 3 .venv file didn't appear and now also it didn't appear.

5.) .gitignore must be committed, this is to ensure that this list of files and folders is ignored and not considered for git commit.

6.) README.md moved from Untracked files to Changes to be committed, as we added README.md to git it committed previously it was untracked.