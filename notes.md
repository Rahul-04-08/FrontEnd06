
// `@media` is a CSS at-rule that is used to apply styles based on specific conditions, such as the
// size of the viewport or the device being used to view the webpage. It allows you to create
// responsive designs that adapt to different screen sizes and devices.

Form controls:
1 Button
2 checkbox
3 radio box
4 search
5 date
6 time
7 text

save 
update 
delete

CRUD


Cookies(4kb)
Cookies are small test files stored in your browser by websites you visit . They help websites remember information about u btw visits

cookies=user identity & authentication btw browser and server

webstorage(5mb)
Web Storage= frontend application state & user performance

1.local storage
2.session storage 

local
1.Local storage is a web storage feature that allows websites to store data in the browser with no expiration time.
2.Thid means the data remains ava even after user clss
3.It is typically used to save long term data such as user perf,themes,login tokens.

session
1.session storage is also browser based storage method,but it only stores data for the duration of single browser tab sessions.
2.once tab is closed,all sessions storage data is automatically deleted.
3.it is useful fot storing temp data like form inputs or nav steps that doesnt need to persist beyond the current session.
4.unlike local storage ,session storage is not sahred across tabs-each tab has its own session.


Git- is a distributed version control system that helps u track changes in ur code,save diff versions of ur proj,and work with others without overwriting each others work.It allows u to create branches,exp safely, and easily go back to older versions whenever needed.

Tool for version control(local machine)

GitHub- Website(by microsoft)to store and manage git repositories online.

Git code commit:
push - up load
pull - down load
pop - delete

Commands:
1.git init-initalize a remote repo
2.git add-add files to staging
3.git commit-save changes to local repo
4.git status-show file changes
5.git clone- copy a remote repo
6.git push-upload commits to repo
7.git pull-download and merge from remote
8.git branch-show branches
9.git checkout-switch branches
10.git remote -v - show connected remote repo

Used daily in real proj commands
11.git log-view commit history
12.git merge-merge another branch
13.git fetch-download updaes withiut merge
14.git switch-modern branch switching
15.git stash-save uncomitted changes
16.git stash pop-restore stashed work
17.git reset-undo staged /committed changes
18.git rm-remove a file
19.git mv-rename/move a file
20.git diff-see diff btw versions














process:
git -v
git init
git remote -v
git remote add origin 
git remote -v
git status
git add "filename for 1 file"
git add .
git branch
git branch -M main
git branch
git status
git commit "msg"
git push -u origin main(if showing error like not stored locally thn use git pull origin main --rebase)
then git push origin main