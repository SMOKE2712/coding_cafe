1.--global means the Git name and email settings apply to all repositories for my user account.If i leave it out,the setting applies only to the current reprisotory.

2. The .git directory appeared in ls -a but not in ls because it is a hidden directory. It contains Git's internal files and folders that store the repository's history, configuration, and
tracking information.

3. Git was offering to track many files and folders, including hundreds of files inside .venv. The .venv files were not written by me; they were created as part of the Python virtual environment.

4. The files and folders inside .venv, along with Python cache files and .DS_Store, disappeared from the untracked files list. They disappeared because the .gitignore file tells Git to ignore them.

5. .gitignore should be committed, not ignored. It contains the rules that tell Git which files and folders to ignore, so keeping it in the repository makes sure the same rules are used by everyone
 working on the project.

6. README.md moved from Changes not staged for commit to Changes to be committed. Running git add README.md moved the changes from the working directory to the staging area, ready for the commit.

7. Git confirmed that the commit was created and displayed the commit ID, branch, message, and summary of the changes. It said that [X] file(s) changed, with the number of insertions and deletions.

8. The first seven characters are a shortened version of the commit hash (commit ID). They are used to identify a specific commit in the Git history without having to write the full hash.

