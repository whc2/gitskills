## push and update
git remote add origin git@github.com:whc2/learn_git.git
git push -u origin master
git remote
git remote -v
git checkout -b dev

## branch 
git branch # check branch
git branch <name>   # create a branch
git checkout <name> # switch to a branch
git checktou -b <name>  # creat and switch to a branch
git merge <name>    # merge a branch with the current branch
git branch -d <name>
git log --graph --pretty=oneline --abbrev-commit
git branch -D <name>    # force rm branch

## deal with bug
git stash   # save working
git stash list  # list stash
git stash pop   # back to a stash and rm it
git stash apply # back to a stash
git stash drop  # rm stash

