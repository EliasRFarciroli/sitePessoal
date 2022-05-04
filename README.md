# sitePessoal




$  git config --global user.name "EliasRFarciroli"



$ $ git config --global user.email elias.20171000900@sobeu.edu.br

Elias@DESKTOP-7AP2RNO MINGW64 ~
$ cd C:/Users/Elias/Desktop/Projetos

Elias@DESKTOP-7AP2RNO MINGW64 ~/Desktop/Projetos
$ git init
Initialized empty Git repository in C:/Users/Elias/Desktop/Projetos/.git/

Elias@DESKTOP-7AP2RNO MINGW64 ~/Desktop/Projetos (master)
$ cd

Elias@DESKTOP-7AP2RNO MINGW64 ~
$ cd C:/Users/Elias/Desktop/Projetos

Elias@DESKTOP-7AP2RNO MINGW64 ~/Desktop/Projetos (master)
$ sites
bash: sites: command not found

Elias@DESKTOP-7AP2RNO MINGW64 ~/Desktop/Projetos (master)
$ cd sites
bash: cd: sites: No such file or directory

Elias@DESKTOP-7AP2RNO MINGW64 ~/Desktop/Projetos (master)
$ cd projetoSites

Elias@DESKTOP-7AP2RNO MINGW64 ~/Desktop/Projetos/projetoSites (master)
$ git init
Initialized empty Git repository in C:/Users/Elias/Desktop/Projetos/projetoSites/.git/

Elias@DESKTOP-7AP2RNO MINGW64 ~/Desktop/Projetos/projetoSites (master)
$ git add Pessoal
error: 'Pessoal/' does not have a commit checked out
fatal: adding files failed

Elias@DESKTOP-7AP2RNO MINGW64 ~/Desktop/Projetos/projetoSites (master)
$ git add /Pessoal
fatal: C:/Program Files/Git/Pessoal: 'C:/Program Files/Git/Pessoal' is outside repository at 'C:/Users/Elias/Desktop/Projetos/projetoSites'

Elias@DESKTOP-7AP2RNO MINGW64 ~/Desktop/Projetos/projetoSites (master)
$ git add /Pessoal
fatal: C:/Program Files/Git/Pessoal: 'C:/Program Files/Git/Pessoal' is outside repository at 'C:/Users/Elias/Desktop/Projetos/projetoSites'

Elias@DESKTOP-7AP2RNO MINGW64 ~/Desktop/Projetos/projetoSites (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Pessoal/
        Sites/

nothing added to commit but untracked files present (use "git add" to track)

Elias@DESKTOP-7AP2RNO MINGW64 ~/Desktop/Projetos/projetoSites (master)
$ git add Pessoal/

Elias@DESKTOP-7AP2RNO MINGW64 ~/Desktop/Projetos/projetoSites (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Pessoal/css/style.css
        new file:   Pessoal/img/linkedin.png
        new file:   Pessoal/index.html
        new file:   Pessoal/js/script.js

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Sites/


Elias@DESKTOP-7AP2RNO MINGW64 ~/Desktop/Projetos/projetoSites (master)
$ git commit -m "Portifólio"
[master (root-commit) 9c42a62] Portifólio
 4 files changed, 24 insertions(+)
 create mode 100644 Pessoal/css/style.css
 create mode 100644 Pessoal/img/linkedin.png
 create mode 100644 Pessoal/index.html
 create mode 100644 Pessoal/js/script.js

Elias@DESKTOP-7AP2RNO MINGW64 ~/Desktop/Projetos/projetoSites (master)
$ git remote add origin https://github.com/EliasRFarciroli/sitePessoal.git

Elias@DESKTOP-7AP2RNO MINGW64 ~/Desktop/Projetos/projetoSites (master)
$ git push -u origin master
info: please complete authentication in your browser...
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (10/10), 5.37 KiB | 1.79 MiB/s, done.
Total 10 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/EliasRFarciroli/sitePessoal.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
