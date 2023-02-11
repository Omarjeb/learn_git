# learn_git

omarj@DESKTOP-KV9VCRE MINGW64 ~/Desktop (master)
$ mkdir learn_git

omarj@DESKTOP-KV9VCRE MINGW64 ~/Desktop (master)
$ cd learn_git

omarj@DESKTOP-KV9VCRE MINGW64 ~/Desktop/learn_git (master)
$ touch third.txt

omarj@DESKTOP-KV9VCRE MINGW64 ~/Desktop/learn_git (master)
$ git init
Initialized empty Git repository in C:/Users/omarj/Desktop/learn_git/.git/

omarj@DESKTOP-KV9VCRE MINGW64 ~/Desktop/learn_git (master)
$ git add .

omarj@DESKTOP-KV9VCRE MINGW64 ~/Desktop/learn_git (master)
$ git commit -m "adding third.txt"
[master (root-commit) 82c0b9a] adding third.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 third.txt

omarj@DESKTOP-KV9VCRE MINGW64 ~/Desktop/learn_git (master)
$ git log
commit 82c0b9a2c8dd7c53fb414f61b00d79bf03103729 (HEAD -> master)
Author: omarjeb <omar.jebali@outlook.com>
Date:   Sat Feb 11 11:46:01 2023 +0100

    adding third.txt

omarj@DESKTOP-KV9VCRE MINGW64 ~/Desktop/learn_git (master)
$ touch fourth.txt

omarj@DESKTOP-KV9VCRE MINGW64 ~/Desktop/learn_git (master)
$ git init
Reinitialized existing Git repository in C:/Users/omarj/Desktop/learn_git/.git/

omarj@DESKTOP-KV9VCRE MINGW64 ~/Desktop/learn_git (master)
$ git add .

omarj@DESKTOP-KV9VCRE MINGW64 ~/Desktop/learn_git (master)
$ git commit -m "adding fourth.txt"
[master b75e863] adding fourth.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 fourth.txt

omarj@DESKTOP-KV9VCRE MINGW64 ~/Desktop/learn_git (master)
$ git rm "third.txt"
rm 'third.txt'

omarj@DESKTOP-KV9VCRE MINGW64 ~/Desktop/learn_git (master)
$ git add .

omarj@DESKTOP-KV9VCRE MINGW64 ~/Desktop/learn_git (master)
$ git commit -m "removing third.txt"
[master b23f8d5] removing third.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 third.txt

omarj@DESKTOP-KV9VCRE MINGW64 ~/Desktop/learn_git (master)
$ git log
commit b23f8d525d66d21fc3de55668434c4776fa4a0ea (HEAD -> master)
Author: omarjeb <omar.jebali@outlook.com>
Date:   Sat Feb 11 11:59:28 2023 +0100

    removing third.txt

commit b75e8635cb8ebeeeffb3b103a76a6dbd673fdcd2
Author: omarjeb <omar.jebali@outlook.com>
Date:   Sat Feb 11 11:52:03 2023 +0100

    adding fourth.txt

commit 82c0b9a2c8dd7c53fb414f61b00d79bf03103729
Author: omarjeb <omar.jebali@outlook.com>
Date:   Sat Feb 11 11:46:01 2023 +0100

    adding third.txt

omarj@DESKTOP-KV9VCRE MINGW64 ~/Desktop/learn_git (master)
$ git config --global user.name "omarjeb"

omarj@DESKTOP-KV9VCRE MINGW64 ~/Desktop/learn_git (master)
$ git config --global user.email "omar.jebali@outlook.com"

omarj@DESKTOP-KV9VCRE MINGW64 ~/Desktop/learn_git (master)
$ git remote add origin https://github.com/Omarjeb/learn_git.git

omarj@DESKTOP-KV9VCRE MINGW64 ~/Desktop/learn_git (master)
$ git push -u origin master
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (7/7), 634 bytes | 211.00 KiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Omarjeb/learn_git.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

omarj@DESKTOP-KV9VCRE MINGW64 ~/Desktop/learn_git (master)
$
