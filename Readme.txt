janrim@LAPTOP-27NVGUGU MINGW64 ~
$ mkdir MEDALLE_IT120_Act1

janrim@LAPTOP-27NVGUGU MINGW64 ~
$ cd MEDALLE_IT120_Act1

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1
$ touch Profile.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1
$ touch Education.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1
$ touch Background.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1
$ touch Readme.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1
$ touch Test.py

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1
$ git init
Initialized empty Git repository in C:/Users/janrim/MEDALLE_IT120_Act1/.git/

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git add .

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Background.txt
        new file:   Education.txt
        new file:   Profile.txt
        new file:   Readme.txt
        new file:   Test.py


janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git commit -m "5 Files Added"
[master (root-commit) 02bf463] 5 Files Added
 5 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Background.txt
 create mode 100644 Education.txt
 create mode 100644 Profile.txt
 create mode 100644 Readme.txt
 create mode 100644 Test.py

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Background.txt
        modified:   Education.txt
        modified:   Profile.txt
        modified:   Test.py

no changes added to commit (use "git add" and/or "git commit -a")

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git add .

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git commit -m "5 files added"
[master a307d5f] 5 files added
 4 files changed, 15 insertions(+)
You sent
janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git branch MEDALLE_B1

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git branch MEDALLE_B2

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git branch MEDALLE_B3

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git branch MEDALLE_B4

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git status
On branch master
nothing to commit, working tree clean

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git branch
  MEDALLE_B1
  MEDALLE_B2
  MEDALLE_B3
  MEDALLE_B4
* master

--Checkout Branch 1

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git checkout MEDALLE_B1
Switched to branch 'MEDALLE_B1'

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B1)
$ git merge master
Already up to date.

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B1)
$ git add Profile.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B1)
$ git commit -m "Additional Info Added to Profile.txt"
[MEDALLE_B1 f1d240d] Additional Info Added to Profile.txt
 1 file changed, 7 insertions(+), 1 deletion(-)

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B1)
$ git status
On branch MEDALLE_B1
nothing to commit, working tree clean

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B1)
$ git add Readme.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B1)
$ git commit -m "Add commands to Readme.txt"
[MEDALLE_B1 7750469] Add commands to Readme.txt
 1 file changed, 119 insertions(+)

--Checkout Branch 2

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B1)
$ git checkout MEDALLE_B2
Switched to branch 'MEDALLE_B2'

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B2)
$ git status
On branch MEDALLE_B2
nothing to commit, working tree clean

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B2)
$ git add Education.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B2)
$ git commit -m "Additional details added to Educationa.txt"
[MEDALLE_B2 ee97eb8] Additional details added to Educationa.txt
 1 file changed, 3 insertions(+)

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B2)
$ git checkout MEDALLE_B1 -- Readme.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B2)
$ git status
On branch MEDALLE_B2
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   Readme.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B3)
$ git add Readme.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B3)
$ git commit -m "Insert commands to Readme.txt"
[MEDALLE_B3 faa08c7] Insert commands to Readme.txt
 1 file changed, 163 insertions(+)

--Checkout Branch 3

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B2)
$ git checkout MEDALLE_B3
Switched to branch 'MEDALLE_B3'

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B3)
$ git status
On branch MEDALLE_B3
nothing to commit, working tree clean

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B3)
$ git add Backround.txt
fatal: pathspec 'Backround.txt' did not match any files

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B3)
$ git add Background.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B3)
$ git commit -m "Updated Background.txt and removed Test.py"
[MEDALLE_B3 81afa33] Updated Background.txt and removed Test.py
 1 file changed, 3 insertions(+), 1 deletion(-)

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B3)
$ git rm Test.py
rm 'Test.py'

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B3)
$ git status
On branch MEDALLE_B3
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    Test.py


janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B3)
$ git commit -m "Remove Test.py"
[MEDALLE_B3 f8eaf76] Remove Test.py
 1 file changed, 2 deletions(-)
 delete mode 100644 Test.py

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B3)
$ git checkout MEDALLE_B2 -- Readme.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B3)
$ git status
On branch MEDALLE_B3
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   Readme.txt


janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B3)
$ git add Readme.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B3)
$ git commit -m "Insert commands"
[MEDALLE_B3 cb4f8a2] Insert commands
 1 file changed, 57 insertions(+), 1 deletion(-)

--Checkout Branch 4

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B3)
$ git checkout MEDALLE_B4
Switched to branch 'MEDALLE_B4'

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B4)
$ git checkout MEDALLE_B3 -- Readme.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B4)
$ git rm Test.py
rm 'Test.py'

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B4)
$ git commit -m "Removed Test.py"
[MEDALLE_B4 ac0136e] Removed Test.py
 2 files changed, 219 insertions(+), 2 deletions(-)
 delete mode 100644 Test.py

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B4)
$ git status
On branch MEDALLE_B4
nothing to commit, working tree clean

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B4)
$ git add Readme.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B4)
$ git commit -m "Inserts Commands"
[MEDALLE_B4 057f5d5] Inserts Commands
 1 file changed, 30 insertions(+)

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (MEDALLE_B4)
$ git checkout master
Switched to branch 'master'

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git checkout MEDALLE_B1 -- Profile.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git checkout MEDALLE_B2 -- Education.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git checkout MEDALLE_B3 -- Background.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git checkout MEDALLE_B4 -- Readme.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   Background.txt
        modified:   Education.txt
        modified:   Profile.txt
        modified:   Readme.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git add Readme.txt

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git commit -m "All Information combined"
[master 09fb7a3] All Information combined
 1 file changed, 31 insertions(+)

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git status
On branch master
nothing to commit, working tree clean

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git commit -m "All Information combined"
[master 8e6c0db] All Information combined
 4 files changed, 273 insertions(+), 2 deletions(-)

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git status
On branch master
nothing to commit, working tree clean

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (master)
$ git branch -M main

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (main)
$ git push -u origin main
info: please complete authentication in your browser...
Enumerating objects: 18, done.
Counting objects: 100% (18/18), done.
Delta compression using up to 12 threads
Compressing objects: 100% (15/15), done.
Writing objects: 100% (18/18), 3.01 KiB | 280.00 KiB/s, done.
Total 18 (delta 5), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (5/5), done.
To https://github.com/kyana20/MEDALLE_IT120_Act1.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (main)
$ git push origin MEDALLE_B1
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 12 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 1.55 KiB | 530.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'MEDALLE_B1' on GitHub by visiting:
remote:      https://github.com/kyana20/MEDALLE_IT120_Act1/pull/new/MEDALLE_B1
remote:
To https://github.com/kyana20/MEDALLE_IT120_Act1.git
 * [new branch]      MEDALLE_B1 -> MEDALLE_B1

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (main)
$ git push origin MEDALLE_B2
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 12 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 1.53 KiB | 781.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 2 local objects.
remote:
remote: Create a pull request for 'MEDALLE_B2' on GitHub by visiting:
remote:      https://github.com/kyana20/MEDALLE_IT120_Act1/pull/new/MEDALLE_B2
remote:
To https://github.com/kyana20/MEDALLE_IT120_Act1.git
 * [new branch]      MEDALLE_B2 -> MEDALLE_B2

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (main)
$ git push origin MEDALLE_B3
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 12 threads
Compressing objects: 100% (11/11), done.
Writing objects: 100% (11/11), 2.11 KiB | 360.00 KiB/s, done.
Total 11 (delta 5), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (5/5), completed with 1 local object.
remote:
remote: Create a pull request for 'MEDALLE_B3' on GitHub by visiting:
remote:      https://github.com/kyana20/MEDALLE_IT120_Act1/pull/new/MEDALLE_B3
remote:
To https://github.com/kyana20/MEDALLE_IT120_Act1.git
 * [new branch]      MEDALLE_B3 -> MEDALLE_B3

janrim@LAPTOP-27NVGUGU MINGW64 ~/MEDALLE_IT120_Act1 (main)
$ git push origin MEDALLE_B4
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 12 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (9/9), 1.91 KiB | 489.00 KiB/s, done.
Total 9 (delta 5), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (5/5), completed with 1 local object.
remote:
remote: Create a pull request for 'MEDALLE_B4' on GitHub by visiting:
remote:      https://github.com/kyana20/MEDALLE_IT120_Act1/pull/new/MEDALLE_B4
remote:
To https://github.com/kyana20/MEDALLE_IT120_Act1.git
 * [new branch]      MEDALLE_B4 -> MEDALLE_B4
