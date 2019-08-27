## push and update
git remote add origin git@github.com:whc2/learn_git.git
git push -u origin master

## branch 
git branch # check branch
git branch <name>   # create a branch
git checkout <name> # switch to a branch
git checktou -b <name>  # creat and switch to a branch
git merge <name>    # merge a branch with the current branch
git branch -d <name>
git log --graph --pretty=oneline --abbrev-commit
git config --list
git log -p -2
git log --stat
git log --since=2.weeks
