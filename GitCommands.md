The following commands can be useful when downloading a specific branch from your github repository to your local repository: <br>
<br>
(1) git init<br>
(2) git pull `<url>`  `<branch>` 
<br>
<br>
 An alternative approach is:
<br>
(1) git init &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; #this would create a new brach called 'master' on your local remote repository. You can either coose to commit tho this new master branch or commit to your existing main branch. However, ***git branch -M `<branch name>`*** will create a brach on your local repository with a specified name.<br> 
(2) git pull `<url>` <br>
(3) git pull origin `<branch>` 
<br>
<br>
Sometimes, you can decide to pull all the existing branch on your repository, before moving to a specific branch, in that case; <br>
(1) git init <br>
(2) git remote add origin `<url>` <br>
(3) git fetch --all <br>
(4) git checkout  `<branch>` <br>
<br>
Also, if you only wat to pull down that specific branch, you can alternatively use; <br>
(1) git init<br>
(2) git remote add origin `<url>` <br>
(3) git fetch origin `<branch>` <br>
(4) git checkout  `<branch>`

<br>
After making changes, use the following line of code to commit and effect the changes on your github repository: <br>

(1) git add . <br>
(2) git commit -m "changes" <br>
(3) git status <br>
(4) git remote -v <br>
(5) git push origin `<branch>`
<br>
<br>
After this first initial changes, subsequent changes can be made by simply using: <br>
(1) git add . <br>
(2) git commit -m "changes" <br>
(3) git push <br>
<br>

When your local repository is not up to date with your remote repository: <br>
(1) First run git status. <br>
(2)Then run git fetch. <br>
(3) Next, run git status again. Git will say your branch is one commit behind. <br>
(4) Finally, run git pull to update your local branch.

