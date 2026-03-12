# 

# C:\\Users\\samer>cd C:\\Users\\samer\\Desktop\\testGit

# 

# C:\\Users\\samer\\Desktop\\testGit>git init

# Initialized empty Git repository in C:/Users/samer/Desktop/testGit/.git/

# 

# C:\\Users\\samer\\Desktop\\testGit>git clone https://github.com/samermaali02-droid/ff.git

# Cloning into 'ff'...

# remote: Enumerating objects: 3, done.

# remote: Counting objects: 100% (3/3), done.

# remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)

# Receiving objects: 100% (3/3), done.

# 

# C:\\Users\\samer\\Desktop\\testGit>git status

# On branch master

# 

# No commits yet

# 

# Untracked files:

# &nbsp; (use "git add <file>..." to include in what will be committed)

# &nbsp;       app.py

# &nbsp;       ff/

# 

# nothing added to commit but untracked files present (use "git add" to track)

# 

# C:\\Users\\samer\\Desktop\\testGit>git add app.py

# 

# C:\\Users\\samer\\Desktop\\testGit>git status

# On branch master

# 

# No commits yet

# 

# Changes to be committed:

# &nbsp; (use "git rm --cached <file>..." to unstage)

# &nbsp;       new file:   app.py

# 

# Untracked files:

# &nbsp; (use "git add <file>..." to include in what will be committed)

# &nbsp;       ff/

# 

# 

# C:\\Users\\samer\\Desktop\\testGit>git commit -m "creation du fichier app.py pour tester github"

# \[master (root-commit) 3827258] creation du fichier app.py pour tester github

# &nbsp;1 file changed, 3 insertions(+)

# &nbsp;create mode 100644 app.py

# 

# C:\\Users\\samer\\Desktop\\testGit>git push origin main

# error: src refspec main does not match any

# error: failed to push some refs to 'origin'

# 

# C:\\Users\\samer\\Desktop\\testGit>git push origin main

# error: src refspec main does not match any

# error: failed to push some refs to 'origin'

# 

# C:\\Users\\samer\\Desktop\\testGit>git branch

# \* master

# 

# C:\\Users\\samer\\Desktop\\testGit>cd ff

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git branch

# \* main

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git push origin main

# Everything up-to-date

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git add app.py

# fatal: pathspec 'app.py' did not match any files

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git add app.py

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git commit -m "creatin du app.py pour tester"

# \[main 3e2f059] creatin du app.py pour tester

# &nbsp;1 file changed, 3 insertions(+)

# &nbsp;create mode 100644 app.py

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git push origin main

# Enumerating objects: 4, done.

# Counting objects: 100% (4/4), done.

# Delta compression using up to 12 threads

# Compressing objects: 100% (2/2), done.

# Writing objects: 100% (3/3), 327 bytes | 81.00 KiB/s, done.

# Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)

# To https://github.com/samermaali02-droid/ff.git

# &nbsp;  684827e..3e2f059  main -> main

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git status

# On branch main

# Your branch is up to date with 'origin/main'.

# 

# nothing to commit, working tree clean

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git status

# On branch main

# Your branch is up to date with 'origin/main'.

# 

# nothing to commit, working tree clean

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git status

# On branch main

# Your branch is up to date with 'origin/main'.

# 

# nothing to commit, working tree clean

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git add app.py

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git status

# On branch main

# Your branch is up to date with 'origin/main'.

# 

# nothing to commit, working tree clean

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git commit -m "creatin du app.py pour tester2"

# On branch main

# Your branch is up to date with 'origin/main'.

# 

# nothing to commit, working tree clean

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git status

# On branch main

# Your branch is up to date with 'origin/main'.

# 

# nothing to commit, working tree clean

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git status

# On branch main

# Your branch is up to date with 'origin/main'.

# 

# Changes not staged for commit:

# &nbsp; (use "git add <file>..." to update what will be committed)

# &nbsp; (use "git restore <file>..." to discard changes in working directory)

# &nbsp;       modified:   app.py

# 

# no changes added to commit (use "git add" and/or "git commit -a")

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git branch testBranch1

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git checkout

# M       app.py

# Your branch is up to date with 'origin/main'.

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git branch

# \* main

# &nbsp; testBranch1

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git checkout testBranch1

# M       app.py

# Switched to branch 'testBranch1'

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git add app.py

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git commit -m "modification app.py"

# \[testBranch1 3eb061e] modification app.py

# &nbsp;1 file changed, 2 insertions(+), 1 deletion(-)

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git push origin testBranch1

# Enumerating objects: 5, done.

# Counting objects: 100% (5/5), done.

# Delta compression using up to 12 threads

# Compressing objects: 100% (2/2), done.

# Writing objects: 100% (3/3), 320 bytes | 80.00 KiB/s, done.

# Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)

# remote:

# remote: Create a pull request for 'testBranch1' on GitHub by visiting:

# remote:      https://github.com/samermaali02-droid/ff/pull/new/testBranch1

# remote:

# To https://github.com/samermaali02-droid/ff.git

# &nbsp;\* \[new branch]      testBranch1 -> testBranch1

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git merge main testBranch1

# Already up to date.

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git checkout test

# error: pathspec 'test' did not match any file(s) known to git

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git checkout main

# Switched to branch 'main'

# Your branch is up to date with 'origin/main'.

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git merge testBranch1

# Updating 3e2f059..3eb061e

# Fast-forward

# &nbsp;app.py | 3 ++-

# &nbsp;1 file changed, 2 insertions(+), 1 deletion(-)

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git add app.py

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git commit -m "merge du deux branches"

# On branch main

# Your branch is ahead of 'origin/main' by 1 commit.

# &nbsp; (use "git push" to publish your local commits)

# 

# nothing to commit, working tree clean

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git push origin main

# Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)

# To https://github.com/samermaali02-droid/ff.git

# &nbsp;  3e2f059..3eb061e  main -> main

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>git log --oneline --graph

# \* 3eb061e (HEAD -> main, origin/testBranch1, origin/main, origin/HEAD, testBranch1) modification app.py

# \* 3e2f059 creatin du app.py pour tester

# \* 684827e Initial commit

# 

# C:\\Users\\samer\\Desktop\\testGit\\ff>.git

