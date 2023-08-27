git clone https://github.com/mattpe/git-intro.git
1 cd .\git-intro\
2 git remote remove origin
3 git remote add origin https://github.com/Glatus/Git-test
4 git remote -v
5 git push -u origin master
6 git commit -u origin master
7 git push -u origin master
8 git branch -M main
9 git push -u origin main
10 touch notes.md
11 nano notes.md
