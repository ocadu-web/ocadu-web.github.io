## A Git Prose

Check the version of your installation `$ git —version`.  Set a user name `$ git config user.name`. Set _(or simply check)_ a user email account `$ git config —global user.email`.

Initialize a working project directory `$ git init` and create a new empty file `$ touch`. Add a draft document to staging `$ git add` and query the status of the project folder/repository `$ git status`. Commit a document to repository `$ git commit -m`. Query difference between working directory and staged documents `$ git diff`, or query difference between staged and last committed documents `$ git diff —staged`, a null response indicates _indifference_. 

Remove an _added_ (or _staged_) file `$ git reset` or abort a merge.  Universally _remove_ `$ git rm` and universally _move_ `$ git mv` files around directories and such.  Remove temporary artifacts and merge conflicts `$ git clean`.

Create a remote connection `$ git remote add origin` after locally committing, so you can push your prose `$ git push origin master` to the cloud.  Flag `$ git push -u origin master` to push repeatedly, while you retrieve `$ git fetch` and pull down `$ git pull origin master ` just as often.  View your repo `$ git show master` and scan your activity `$ git log` while back and forth cloud travel normalizes`$ git push` `$ git fetch` `$ git pull `.

Trees branch `$ git branch` to and fro `$ git checkout -b` and back again `$ git branch planet master^`.  Lost?  Get yourself a map to navigate `$ tree .git/refs`.

_© 2018_

<!--  
$ git push origin planet —set-upstream
$ git clone
$ git branch -d planet
$ git branch -vv
$ git branch -no—merged -->