
# -finding_donors
## Pushing new file on Git repitory 
 ~/Documents/Python_DataAnalyst/udacity/projects/charityml/p1_charityml (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   finding_donors.ipynb

no changes added to commit (use "git add" and/or "git commit -a")

 ~/Documents/Python_DataAnalyst/udacity/projects/charityml/p1_charityml (master)
$ git add .
warning: LF will be replaced by CRLF in finding_donors.ipynb.
The file will have its original line endings in your working directory

/Documents/Python_DataAnalyst/udacity/projects/charityml/p1_charityml (master)
$ git commit -m "finding_donors update"
[master 07574e7] finding_donors update
 1 file changed, 94 insertions(+), 71 deletions(-)

~/Documents/Python_DataAnalyst/udacity/projects/charityml/p1_charityml (master)
$ git push origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 68.12 KiB | 3.58 MiB/s, done.
Total 3 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/tramchip/-finding_donors.git
   3c89fb4..07574e7  master -> master

~/Documents/Python_DataAnalyst/udacity/projects/charityml/p1_charityml (master)


---------------------------------------------



to convert notebook to html after any changes, type

~/anaconda2/bin/jupyter-nbconvert --to html finding_donors.ipynb
