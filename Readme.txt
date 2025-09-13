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

