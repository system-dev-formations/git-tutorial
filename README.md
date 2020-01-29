# git-labs
```shell script
   git remote -v
   git config --global user.name "Herve"
   git config --global user.email dockerlite@gmail.com
   # mettre des aliases
   git config --global alias.br branch
   git config --global alias.ci commit
   git config --global alias.st status
   git config --global alias.last 'log -1 HEAD'
   cat ~/.gitconfig
   git config --global -e 
   git config --global core.editor vi
   git config --help
   echo content > file1.c    
   git st
   git add file1.c 
   git st 
   git commit -m "my content"
   git log
   echo more > file1.c
   git add file1.c
   echo more_info > file1.c
   git st 
   git ls-files --stage
   git commit -m "exemple 2"
   git status
   git log -1
   git add file1.c
   git commit -am "Nouveau fichier"
   git mv test.py
   git rm test.py 
   git rm --cached  test.py 
   git log -1 --stat 
  git log --oneline -4
  git hist
  git diff 
  git diff --cached 
  git diff HEAD 
  git blame file1.c
  git log -S "web framework"
  git reset --hard HEAD 
  git reset <hash_du_commit>
  git commit --amend
  git log -1 --stat
  git log --oneline -4
  git log --oneline -1
  git log --oneline -2
  git hist
  git diff
  git hist
  git  diff 746fba9..HEAD
  git blame myfile.c
  git hist
  echo MyVersion > myversion.c
  git add myversion.c
   git commit -m "MyVersion de langage C"
    vi myversion.c
    git commnit - m "autre version amend" --amend
   git commit -m "MyVersion de langage C"  --amend
    git log
   vi myversion.c
    git commit -m "MyVersion"  --amend
    git log
     vi myversion.c
     git commit  --amend --no-edit
    git checkout <valeur_du_hash>
    git tag v1.1
    git tag v1.2 <valeur_du_hash>
    git push origin --tags
    git tag -d v1.1  # en local
    git push orgin :refs/tags/v1.1  # remote
    git branch
    git branch  -v
    git check-ref-format --branch 2.x/fix/ticket/3245
   
    











   


  
















   
```