$ history
    1  eval "$(ssh-agent -S)"
    2  eval "$(ssh-agent -s)"
    3  ssh-add ~/.ssh/id_ed25519
    4  clip < ~/.ssh/id_ed25519.pub
    5  ls
    6  cd Desktop/
    7  mkdir exemplo
    8  cd exemplo/
    9  ls -la
   10  git init
   11  ls -la
   12  git status
   13  nano teste
   14  nano teste.md
   15  git status
   16  git add .
   17  git status
   18  git rm --cached teste.md
   19  git status
   20  git commit -m "meu primeiro commit"
   21  git branch
   22  git checkout -b dev
   23  git status
   24  ls -la
   25  git status
   26  git branch
   27  nano teste2.md
   28  ls -ls
   29  ls -la
   30  git add .
   31  git status
   32  git commit -m "meu segundo commit"
   33  git checkout 'master'
   34  git merge dev
   35  git branch -d dev
   36  git branch
   37  history
   38  cd ..
   39  rm -rf exemplo/
   40  git clone git@github.com:DayaneNogueira/portifolio.git
   41  cd portifolio/
   42  code .