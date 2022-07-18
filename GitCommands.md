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
(3) git push