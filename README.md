Mi Prueba
Adjunto prueba de  como subi el proyecto

PS C:\Users\Omar\Pictures\assets> git init
Initialized empty Git repository in C:/Users/Omar/Pictures/assets/.git/
PS C:\Users\Omar\Pictures\assets> git add .
PS C:\Users\Omar\Pictures\assets> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   css/style.css
        new file:   img/coupon.jpeg
        new file:   img/cv.jpeg
        new file:   img/iguanapage.jpeg
        new file:   img/linkedin.png
        new file:   img/profilepic.jpeg
        new file:   img/profilepic.png
        new file:   img/profpic.jpeg
        new file:   img/tienda.jpeg
        new file:   index.html

PS C:\Users\Omar\Pictures\assets> git commit -m "First Commit"
[master (root-commit) 5e3edd9] First Commit
 10 files changed, 395 insertions(+)
 create mode 100644 css/style.css
 create mode 100644 img/coupon.jpeg
 create mode 100644 img/cv.jpeg
 create mode 100644 img/iguanapage.jpeg
 create mode 100644 img/linkedin.png
 create mode 100644 img/profilepic.jpeg
 create mode 100644 img/profilepic.png
 create mode 100644 img/profpic.jpeg
 create mode 100644 img/tienda.jpeg
 create mode 100644 index.html
 
PS C:\Users\Omar\Pictures\assets> git status
On branch master
nothing to commit, working tree clean
PS C:\Users\Omar\Pictures\assets> git remote add origin https://github.com/Oapa08/Oapa08.github.io.git

PS C:\Users\Omar\Pictures\assets> git branch -M main

PS C:\Users\Omar\Pictures\assets> git push -u origin main                                  
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 4 threads
Compressing objects: 100% (13/13), done.
Writing objects: 100% (14/14), 849.04 KiB | 7.38 MiB/s, done.
Total 14 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Oapa08/Oapa08.github.io.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

