 787  cd
  788  ls
  789  cd Documents
  790  ls
  791  cd GitHub
  792  ls
  793  mkdir bashGit
  794  ls
  795  cd bashGit
  796  git init
  797  git push
  798  git remote add master https://github.com/dafhome/bashGit.git
  799  git push
  800  git push --set-upstream master master
  801  git remote --v
  802  git push --set-upstream master master
  803  git add README.md
  804  touch README.md
  UW PICO 5.09                                                           New Buffer












































                                                                [ Read 1 line ]
^G Get Help             ^O WriteOut             ^R Read File            ^Y Prev Pg              ^K Cut Text             ^C Cur Pos
^X Exit                 ^J Justify              ^W Where is             ^V Next Pg              ^U UnCut Text           ^T To Spell
  805  git add README.md
  806  git commit -m "commit"
  807  git branch -M main
  808  git push -u master main
  809  mkdir HolaMundo
  810  cd HolaMundo
  811  touch index.html
  812  ls -a
  813  cd ..
  814  ls
  815  git add HolaMundo/
  816  git commit -m "añadir_carpeta"
  817  git push -u master main
  818  cd HolaMundo
  819  nano index.html
  820  code index.html
  821  cd ..
  822  git add HolaMundo/
  823  git commit -m "cambios_index_html"
  824  git push -u master main
12f37a8 (HEAD -> main, master/main) cambios_index_html
aa6e4e4 añadir_carpeta
fd6f638 commit
...skipping...
  825  history --online
  826  git log
  827  git history
  828  git --help
12f37a8 (HEAD -> main, master/main) cambios_index_html
aa6e4e4 añadir_carpeta
fd6f638 commit
(END)
