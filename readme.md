#Git Commands

<!--show git commits in one line  -->
* git log --oneline --graph

<!--shows not linear version working locally and merging  -->
* git merge --no-ff some-branch-name

<!--display changes in commit  -->
* git show commit-hash-number

 <!--show changes in most recent commit  -->
* git show HEAD

<!--adds new staged files/file into recent commit  -->
* git commit --amend

 <!--show changes in most recent commit  -->
* git diff commit-hash-number

<!--adds new staged files/file into recent commit  -->
* git diff HEAD

<!-- Return to a particular point in history. All changes made after this commit are moved “not yet staged for commit” stage. Meaning you would have to run git add . and git commit to add them back in. -->
* git reset {{some-commit-hash}}
