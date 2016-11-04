*git init*
Create a repo from existing data

*git clone (repo_url)*
Clone a current repo (into a folder with same name as repo)

*git clone (repo_url) (folder_name)*
Clone a repo into a specific folder name

*git clone (repo_url) .*
Clone a repo into current directory (should be an empty directory)

*git remote add origin https://github.com/username/(repo_name).git*
Create a remote repo named origin pointing at your Github repo (after you’ve already created the repo on Github) (used if you git init since the repo you created locally isn’t linked to a remote repo yet)

*git remote add origin git@github.com:username/(repo_name).git*
Create a remote repo named origin pointing at your Github repo (using SSH url instead of HTTP url)

*git remote*
Show the names of the remote repositories you’ve set up

*git remote -v*
Show the names and URLs of the remote repositories

*git remote rm (remote_name)*
Remove a remote repository

*git remote set-url origin (git_url)*
Change the URL of the git repo

*git push*
Push your changes to the origin
