acer@LAPTOP-IKAIGSD3 MINGW32 ~
$ mkdir git-basic

acer@LAPTOP-IKAIGSD3 MINGW32 ~
$ cd git-basic

acer@LAPTOP-IKAIGSD3 MINGW32 ~/git-basic
$ touch first.txt

acer@LAPTOP-IKAIGSD3 MINGW32 ~/git-basic
$ git init .
Initialized empty Git repository in C:/Users/acer/git-basic/.git/

acer@LAPTOP-IKAIGSD3 MINGW32 ~/git-basic (master)
$ git add .

acer@LAPTOP-IKAIGSD3 MINGW32 ~/git-basic (master)
$ git commit -m "adding first.txt"
[master (root-commit) ba1a81c] adding first.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 first.txt

acer@LAPTOP-IKAIGSD3 MINGW32 ~/git-basic (master)
$ git log
commit ba1a81c1743becdea71d850fff63873e59ec65a1 (HEAD -> master)
Author: zackyaje <m.zackynauvaldi123@gmil.com>
Date:   Thu Jul 28 08:44:14 2022 +0700

    adding first.txt

acer@LAPTOP-IKAIGSD3 MINGW32 ~/git-basic (master)
$ touch second.txt

acer@LAPTOP-IKAIGSD3 MINGW32 ~/git-basic (master)
$ git add second.txt

acer@LAPTOP-IKAIGSD3 MINGW32 ~/git-basic (master)
$ git commit -m "adding second.txt"
[master 469c0df] adding second.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 second.txt

acer@LAPTOP-IKAIGSD3 MINGW32 ~/git-basic (master)
$ rm first.txt

acer@LAPTOP-IKAIGSD3 MINGW32 ~/git-basic (master)
$ git add .

acer@LAPTOP-IKAIGSD3 MINGW32 ~/git-basic (master)
$ git commit -m "removing first.txt"
[master afba7bb] removing first.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 first.txt

acer@LAPTOP-IKAIGSD3 MINGW32 ~/git-basic (master)
$ git log
commit afba7bbd10376a9eef00b626b22236903754f1c1 (HEAD -> master)
Author: zackyaje <m.zackynauvaldi123@gmil.com>
Date:   Thu Jul 28 08:46:32 2022 +0700

    removing first.txt

commit 469c0dfdb35cc6135f656f823b607818cdf93f63
Author: zackyaje <m.zackynauvaldi123@gmil.com>
Date:   Thu Jul 28 08:45:38 2022 +0700

    adding second.txt

commit ba1a81c1743becdea71d850fff63873e59ec65a1
Author: zackyaje <m.zackynauvaldi123@gmil.com>
Date:   Thu Jul 28 08:44:14 2022 +0700

    adding first.txt
