

Author: Swapnil Ranbhise

Git Hub notes:<br>
git clone : used for clonning the repo in your local system <br>
git status: gets the status <br>
untracked: new files that git doesn't yet track <br>
modified: changed <br>
staged: file is ready to be commit <br>
unmodified: unchanged <br>

basic steps : 1) ADD 2) COMMIT <br>

git add. -> All your modification/changes gets staged for commit. <br>
git add <file_name> -> change gets staged for commit. <br>
git commit -m "some_message" -> commit changes/ save changes. Always write some message while commit or it will give error in vscode. <br>
git push origin main -> All your commit changes gets pushed into github repo.<br>
git init -> used to create a new git repo in vscode.<br>
git remote add origin <link> -> <br>
git remote -v -> to verify remote <br>

Branch Commands: <br>
git branch -> to check branch <br>
git branch -M main -> to rename branch
git checkout <branch_name>  ->  to navigate <br>
git checkout -b <name_branch_name> -> to create new branch. <br>
git branch -d <branch_name> -> to delete branch. <br>

Merging code: <br>
Way1:
git diff <branch_name> -> to compare , branches, files and more. <br>
git merge <branch_name> -> to merge 2 branches. <br>

Way2:(github): <br>
create a PR(pull request) <br>
git pull origin main -> pull command(vs_code).<br>

Undoing Changes: <br>
staged changes:<br>
git reset <file_name> <br>
git reset   <br>

changes for one commit: <br>
git reset HEAD-1 <br>

commited changes (for many commits) :<br>
git reset <commit hash> <br>
git reset __hard <commit hash> <br>

Fork: This feature is used when you want to make a copy of someone else repo and paste it into your repository.<br>
Pull Request : This is used when you want to merge branches, or some edits you make and you want to merge it into main.<br>
Branches: they allow us to collaborate . Diffrent individuals can work on different features and then merge it to the mani project. <br>







