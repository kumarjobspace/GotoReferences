### GIT Commands
* https://github.com/k88hudson/git-flight-rules#i-want-to-start-a-local-repository
* Commit a particular file
  * git add Database/FQHCLA_5_0_0_Deployment_Steps.xlsx - Stage
  * git commit -m 'changed db steps' - Commit
  * git undo all uncommitted or unsaved changes : https://stackoverflow.com/questions/14075581/git-undo-all-uncommitted-or-unsaved-changes

* Delete local branch -> git branch -D <branch_name> 
* Delete Remote branch -> git push origin --delete <your_branch>
* git undo all uncommitted or unsaved changes - 
   * https://stackoverflow.com/questions/14075581/git-undo-all-uncommitted-or-unsaved-changes/24833738
   * This will unstage all files you might have staged with git add:
      git reset
   * This will revert all local uncommitted changes (should be executed in repo root):
      git checkout .
   * You can also revert uncommitted changes only to particular file or directory:
      git checkout [some_dir|file.txt]
* Rename branch - https://stackoverflow.com/questions/30590083/how-to-rename-a-remote-git-branch-name
   * rename the local branch to the new name => git branch -m old_name new_name 
   * delete the old branch on remote - where <remote> is eg. origin => git push <remote> --delete old_name
   * push the new branch to remote => git push <remote> new_name



### Links
* Merge => https://stackoverflow.com/questions/14168677/merge-development-branch-with-master
https://stackoverflow.com/questions/9834689/comparing-two-branches-in-git
* Git Cheat Sheet - http://danielkummer.github.io/git-flow-cheatsheet/
* Git Flow Comparision - https://gist.github.com/JamesMGreene/cdd0ac49f90c987e45ac

# Git Tutorials:
* https://www.atlassian.com/git/tutorials
* https://www.codeschool.com/learn/git
* Git Playground - https://try.github.io/levels/1/challenges/1
* Git from the Inside Out  - https://codewords.recurse.com/issues/two/git-from-the-inside-out
* Git from the Bottom Up - https://jwiegley.github.io/git-from-the-bottom-up/
* Git WorkFlow With Diagram - http://blog.osteele.com/2008/05/my-git-workflow/
* Git Book - https://git-scm.com/book/en/v2
* Stackoverflow questions on Git
  * http://data.stackexchange.com/stackoverflow/query/36656/most-upvoted-answers
  * How to undo the last commit in Git - https://stackoverflow.com/questions/927358/how-to-undo-the-last-commits-in-git#927386
  * How do I delete a Git branch both locally and remotely? - https://stackoverflow.com/questions/2003505/how-do-i-delete-a-git-branch-both-locally-and-remotely/2003515#2003515
  * How to modify existing, unpushed commits? - https://stackoverflow.com/questions/179123/how-to-modify-existing-unpushed-commits/179147#179147
  * How do I rename a local Git branch? - https://stackoverflow.com/questions/6591213/how-do-i-rename-a-local-git-branch/6591218#6591218
  * What is the difference between 'git pull' and 'git fetch'? - https://stackoverflow.com/questions/292357/what-is-the-difference-between-git-pull-and-git-fetch/292359#292359
  * How to revert Git repository to a previous commit? - https://stackoverflow.com/questions/4114095/how-to-revert-git-repository-to-a-previous-commit/4114122#4114122
  * How to remove local (untracked) files from the current Git working tree? - https://stackoverflow.com/questions/61212/how-to-remove-local-untracked-files-from-the-current-git-working-tree/64966#64966
  * http://ohshitgit.com/
  * http://hn.premii.com/#/article/15951825



## GitHub blog 
* https://github.com/kilimchoi/engineering-blogs
* https://github.com/sindresorhus/awesome
