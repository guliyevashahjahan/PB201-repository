Used commands:


ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop
$ mkdir PB201

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop
$ cd PB201

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201
$ touch Github.txt

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201
$ git init
Initialized empty Git repository in C:/Users/ASUS/Desktop/PB201/.git/

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201 (master)
$ git add .

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201 (master)
$ git commit -m "created github text file"
[master (root-commit) d1743d6] created github text file
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Github.txt

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201 (master)
$ git remote add origin https://github.com/guliyevashahjahan/PB201-repository.git

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201 (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 228 bytes | 228.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/guliyevashahjahan/PB201-repository.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201 (master)
$ git branch development

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201 (master)
$ git checkout development
Switched to branch 'development'

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201 (development)
$ touch development.txt

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201 (development)
$ git push -u origin development
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'development' on GitHub by visiting:
remote:      https://github.com/guliyevashahjahan/PB201-repository/pull/new/development
remote:
To https://github.com/guliyevashahjahan/PB201-repository.git
 * [new branch]      development -> development
branch 'development' set up to track 'origin/development'.

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201 (development)
$ git add .

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201 (development)
$ git commit -m "created development branch"
[development 8cc4a11] created development branch
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 development.txt

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201 (development)
$ git push -u origin development
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 268 bytes | 268.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/guliyevashahjahan/PB201-repository.git
   d1743d6..8cc4a11  development -> development
branch 'development' set up to track 'origin/development'.

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201 (development)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201 (master)
$ git merge development
Updating d1743d6..8cc4a11
Fast-forward
 development.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 development.txt

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201 (master)
$ git add .

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201 (master)
$ git commit -m "merged development branch"
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201 (master)
$ git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/guliyevashahjahan/PB201-repository.git
   d1743d6..8cc4a11  master -> master

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201 (master)
$ git branch feature

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201 (master)
$ git checkout feature
Switched to branch 'feature'

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201 (feature)
$ mkdir feature

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201 (feature)
$ cd feature

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201/feature (feature)
$ touch feature.txt

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201/feature (feature)
$ git add .

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201/feature (feature)
$ git commit -m "created feature branch"
[feature e7a081e] created feature branch
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 feature/feature.txt

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201/feature (feature)
$ git push -u origin feature
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 345 bytes | 345.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'feature' on GitHub by visiting:
remote:      https://github.com/guliyevashahjahan/PB201-repository/pull/new/feature
remote:
To https://github.com/guliyevashahjahan/PB201-repository.git
 * [new branch]      feature -> feature
branch 'feature' set up to track 'origin/feature'.

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201/feature (feature)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201/feature (master)
$ git merge feature
Updating 8cc4a11..e7a081e
Fast-forward
 feature/feature.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 feature/feature.txt

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201/feature (master)
$ git add .

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201/feature (master)
$ git commit -m "merged feature branch"
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201/feature (master)
$ git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/guliyevashahjahan/PB201-repository.git
   8cc4a11..e7a081e  master -> master

ASUS@DESKTOP-97I67TG MINGW64 ~/Desktop/PB201/feature (master)
$
