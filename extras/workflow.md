# Workflow

This is the actual workflow I like to use in my projects, I found describing it step by step helps those who are new to git.

_So, you want to start working on a new feature or fix some problem:_

1. git pull
2. create a branch `git branch branch-name`
3. switch to it `git switch branch-name`
4. work (modify files $\to$ add $\to$ commit, complete the task, etc)
5. git pull (again)
6. stay in the your feature, and merge main _into_ your branch
7. verify everything is alright and nothing broken
8. push the feature branch `git push -u origin branch-name`
   - note: do not forget the `-u` because it is the first time you push the branch
9. open github, and create a pull request (PR) in Github
   - note: describe the changes you made
10. wait and discuss with the team leader
    - note: if there is a problem
      - fix it
      - commit it
      - `git push` (no need for `-u`)
      - DO NOT create a new pull request, the old pull request will follow the latest commit automatically
11. The team leader will merge the pull request
12. delete the branch in Github
13. switch to main: `git switch main`
14. `git pull`
15. delete the local branch: `git branch -d branch-name`
16. delete the remote tracking branch (origin/branch-name): `git fetch -p`

NOTE: why step 6?
Well, I learned this the hard way :D
we usually merge the feature 🍫 into main🎂 (remember the cake analogy)
This time we did the opposite, we merge the main into feature because we want to verify if there are conflicts that PR won't catch, the fact that there are no conflicts in the merge doesn't mean it's working.
The way git finds conflicts in merge is text based, but it doesn't account for semantic problems, for example perhaps someone in main branch removed a function you're using in your code, git won't catch that!
That's why you merge main into your branch so you have all the changes, and you can locally see if you have compiler errors, etc.

NOTE: what's the cake analogy?
It's a simple way to remember where you should be when you merge, you usually switch to main (the cake, the big thing) and do `git merge feature`, the feature is the chocolate :D

#### Git Conventions

**Commits:** chore/fix/feat/refactor
examples:

- docs: update readme file
- chore: add gitignore file
- fix: error in colors
- feat: add a new scene
- refactor: use async instead of promise syntax
