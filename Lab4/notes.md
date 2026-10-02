1.) Basically, --global is used to save one's Email-Id and name throughout the system for all users for all the repositories created using git. If --global isn't used then the name and Email-Id is only valid for the current working repository and not for all repositories.

2.) In ls only the folders and files are visible but hidden folders starting with a dot(.) are invisible using ls -a displays all of the files, folders and hidden folders as well.

3.) Git has no limitations it can track all of the files and folders; the only catch is that it can't track hidden folders which start with dot(.).

4.) Nothing actually disappeared actually .gitignore was the extra file that appeared on the list, initially in the question 3 .venv file didn't appear and now also it didn't appear.

5.) .gitignore must be committed, this is to ensure that this list of files and folders is ignored and not considered for git commit.

6.) README.md moved from "Untracked files" to "Changes to be committed", as we added README.md to git it committed, previously it was untracked.

7.) Git printed create mode 100644 and the file/folder name for all 5 items (3 folders and 2 files).

8.) The first seven characters are called short commit hash (or short SHA-1 / commit SHA). They are used to identify files/folders which are committed.

9.) i. check git status | ii. git add file name | iii. git commit -m "name"| iv. git log --online.

10.) README.md is a document which gives a brief about the user and the file that the user is about to write about.

11.) gh auth login is used to link our GitHub account with our local git repository, while pushing our repository into our GitHub account it doesn't repeatedly ask for password.

12.) The repository page on GitHub contains Lab4, README.md, .gitignore and week02. These files and folders were uploaded through git and hence they are showing up.

13.) No, the local history remains the same; Previously the output was "908ba46 (HEAD -> master) Lab work so far" now along with that this was also printed "5231206 (HEAD -> main, origin/main) Write README".

14.) When a repository is set to private it can only be accessed by us and our collaborators, when a repository isn't on GitHub it only exists locally in our computer.