# belajarGIT
Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT
…

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT
$ git clone https://github.com/Berylboch14/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 12, done.
remote: Counting objects: 100% (12/12), done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 12 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (12/12), done.

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT
$ cd belajarGIT

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (main)
$ git branch Tugas-html

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (main)
$ git checkout Tugas-git
Switched to a new branch 'Tugas-git'
branch 'Tugas-git' set up to track 'origin/Tugas-git'.

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-git)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-html)
$ touch "Tugas-html.txt"

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-html.txt


user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-html)
$ git commit -m "Tugas-html.txt"
[Tugas-html 511643d] Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-html)
$ git push origin Tugas-html
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 6 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 290 bytes | 145.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-html' on GitHub by visiting:
remote:      https://github.com/Berylboch14/belajarGIT/pull/new/Tugas-html
remote:
To https://github.com/Berylboch14/belajarGIT.git
 * [new branch]      Tugas-html -> Tugas-html

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-html)
$ git branch Tugas-css

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-html)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-css)
$ git commit -m "Tugas-css.txt"
[Tugas-css f8d9e0e] Tugas-css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-css)
$ git push origin Tugas-css
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 6 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 313 bytes | 156.00 KiB/s, done.
Total 3 (delta 0), reused 1 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-css' on GitHub by visiting:
remote:      https://github.com/Berylboch14/belajarGIT/pull/new/Tugas-css
remote:
To https://github.com/Berylboch14/belajarGIT.git
 * [new branch]      Tugas-css -> Tugas-css

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-css)
$ git branch Tugas-js

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-css)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-js)
$ touch Tugas-php.txt

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-js)
$ git commit -m "Tugas-js.txt"
[Tugas-js 113c5b4] Tugas-js.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-js)
$ git push origin Tugas-js
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 6 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 265 bytes | 265.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Tugas-js' on GitHub by visiting:
remote:      https://github.com/Berylboch14/belajarGIT/pull/new/Tugas-js
remote:
To https://github.com/Berylboch14/belajarGIT.git
 * [new branch]      Tugas-js -> Tugas-js

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-js)
$ git branch Tugas-midProject

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-js)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-midProject)
$ touch Tugas-midProjec.txt

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt
fatal: pathspec 'Tugas-midProject.txt' did not match any files

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-midProject)
$  git add Tugas-midProject.txt

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-midProject)
$ git commit -m "Tugas-midProject.txt"
[Tugas-midProject 5afcfa2] Tugas-midProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-midProject)
$ git push origin Tugas-midProject
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 6 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 276 bytes | 276.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Tugas-midProject' on GitHub by visiting:
remote:      https://github.com/Berylboch14/belajarGIT/pull/new/Tugas-midProject
remote:
To https://github.com/Berylboch14/belajarGIT.git
 * [new branch]      Tugas-midProject -> Tugas-midProject

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-midProject)
$ git checkout Tugas-php
error: pathspec 'Tugas-php' did not match any file(s) known to git

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-midProject)
$ git branch Tugas-php

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-midProject)
$ touch Tugas-php.txt

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-midProject)
$ git add Tugas-php.txt

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-midProject)
$ git commit -m "Tugas-php.txt"
[Tugas-midProject ec6d30a] Tugas-php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-midProject)
$ git push origin Tugas-php
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-php' on GitHub by visiting:
remote:      https://github.com/Berylboch14/belajarGIT/pull/new/Tugas-php
remote:
To https://github.com/Berylboch14/belajarGIT.git
 * [new branch]      Tugas-php -> Tugas-php

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-midProject)
$ git branch Tugas-finalProject

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-midProject)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-finalProject)
$ git commit -m  "Tugas-finalProject.txt"
[Tugas-finalProject a737d94] Tugas-finalProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-finalProject)
$ git push origin Tugas-finalProject
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 6 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 458 bytes | 229.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
remote:
remote: Create a pull request for 'Tugas-finalProject' on GitHub by visiting:
remote:      https://github.com/Berylboch14/belajarGIT/pull/new/Tugas-finalProject
remote:
To https://github.com/Berylboch14/belajarGIT.git
 * [new branch]      Tugas-finalProject -> Tugas-finalProject

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-finalProject)
$ git pull
remote: Enumerating objects: 46, done.
remote: Counting objects: 100% (36/36), done.
remote: Compressing objects: 100% (24/24), done.
remote: Total 29 (delta 10), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (29/29), 11.53 KiB | 39.00 KiB/s, done.
From https://github.com/Berylboch14/belajarGIT
   f8d9e0e..14480f8  Tugas-css          -> origin/Tugas-css
   a737d94..14c31b6  Tugas-finalProject -> origin/Tugas-finalProject
   113c5b4..47be6ac  Tugas-js           -> origin/Tugas-js
   5afcfa2..f812a7e  Tugas-midProject   -> origin/Tugas-midProject
   014f3a4..5c7c4a6  main               -> origin/main
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> Tugas-finalProject


user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-finalProject)
$ git push origin --all
To https://github.com/Berylboch14/belajarGIT.git
 ! [rejected]        Tugas-css -> Tugas-css (non-fast-forward)
 ! [rejected]        Tugas-finalProject -> Tugas-finalProject (non-fast-forward)
 ! [rejected]        Tugas-js -> Tugas-js (non-fast-forward)
 ! [rejected]        Tugas-midProject -> Tugas-midProject (non-fast-forward)
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/Berylboch14/belajarGIT.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. If you want to integrate the remote changes,
hint: use 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is behind 'origin/main' by 21 commits, and can be fast-forwarded.
  (use "git pull" to update your local branch)

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (main)
$ git pull
Updating 014f3a4..5c7c4a6
Fast-forward
 Tugas-Git.txt          | 1 +
 Tugas-css.txt          | 1 +
 Tugas-finalProject.txt | 1 +
 Tugas-html.txt         | 1 +
 Tugas-js.txt           | 1 +
 Tugas-midProject.txt   | 1 +
 Tugas-php.txt          | 1 +
 7 files changed, 7 insertions(+)
 create mode 100644 Tugas-Git.txt
 create mode 100644 Tugas-css.txt
 create mode 100644 Tugas-finalProject.txt
 create mode 100644 Tugas-html.txt
 create mode 100644 Tugas-js.txt
 create mode 100644 Tugas-midProject.txt
 create mode 100644 Tugas-php.txt

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (main)
$ git push origin --all
To https://github.com/Berylboch14/belajarGIT.git
 ! [rejected]        Tugas-css -> Tugas-css (non-fast-forward)
 ! [rejected]        Tugas-finalProject -> Tugas-finalProject (non-fast-forward)
 ! [rejected]        Tugas-js -> Tugas-js (non-fast-forward)
 ! [rejected]        Tugas-midProject -> Tugas-midProject (non-fast-forward)
error: failed to push some refs to 'https://github.com/Berylboch14/belajarGIT.git'
hint: Updates were rejected because a pushed branch tip is behind its remote
hint: counterpart. If you want to integrate the remote changes, use 'git pull'
hint: before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (main)
$ git pull origin main
From https://github.com/Berylboch14/belajarGIT
 * branch            main       -> FETCH_HEAD
Already up to date.

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (main)
$ ^C

user@LAPTOP-JOJNC7Q8 MINGW64 ~/OneDrive/Desktop/GIT/belajarGIT (main)
$
