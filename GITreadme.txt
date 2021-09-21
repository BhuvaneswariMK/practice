git config --global user.name bhuvaneswari.m.kulandaivelu@gmail.com
git config --global user.name BhuvaneswariMK
git config --global user.email bhuvaneswari.m.kulandaivelu@gmail.com
C:\JavaPractices>git init
Initialized empty Git repository in C:/JavaPractices/.git/

C:\JavaPractices>git clone /path/to/repository
fatal: repository '/path/to/repository' does not exist

C:\JavaPractices>git add readme.md
fatal: pathspec 'readme.md' did not match any files
C:\JavaPractices>git add FirstProgram.java

C:\JavaPractices>git commit -m "first commit"
[master (root-commit) fcddce6] first commit
 1 file changed, 6 insertions(+)
 create mode 100644 FirstProgram.java

C:\JavaPractices>git branch -M main

C:\JavaPractices>git remote add origin https://github.com/BhuvaneswariMK/Project1.git

C:\JavaPractices>git push -u origin main
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 344 bytes | 86.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/BhuvaneswariMK/Project1.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

C:\JavaPractices>



































































