# 2021-11-03-git_collab
1. Edit the readme.md file
2. Mention define git clone
3. add the changes to the stagin area
---------------------------------------------
1. git clone
2. git branch - git branch <name> -- <name> where is HEAD IS
3. git branch - a: shows all your branches, including the remote.
4. git switch: move the <branch> after creating it.
5. git checkout <name> - older way to switch.
-----------------------------------------------
1. git log --oneline --graph --all: shows you the git log wih all the branches and histroy.
1.1 git switch -c: create and switch to the branch in a single step.
1.2 git branch -b: older way of doing the above.
2. pull request: (aka merge request), doing a merge on the remote(ex. Github)
2.1  PR will, by default, auto update if with new commits in the same branch, yes agree.
2.2 many commits in the same PR confirmed with the git --graph locally.
2.3 Git stash: makes a temp commit with current changes
    git stash pop takes the last stash and re-applies it.

--------------------------------------------------------------
git fetch --prune
git branch -d <branch_name>: delete the branch, will fail if branch is not merged.
git branch -D <branch_name>: delete the branch even if not merged.