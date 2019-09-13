1  git
 
2  pwd
 
3  cd .ssh
 
4  ls -a
 
5  mkdir .ssh
 
6  cd .ssh
 
7  ls -alt
 
8  ssh-keygen
 
9  ls
 
10  cat id_rsa.pub
 
11  git config --global user.name "Sarah Kurisu"
 
12  git config --global user.email "sarah.kurisu@gmail.com"
 
13  git config --list
 
14  cd
 
15  mkdir gitSetup
 
16  cd gitSetup/
 
17  touch README.md
 
18  git status
 
19  git init
 
20  git add README.md
 
21  git commit -m "initial commit"
 
22  git remote add origin git@github.com:skurisu/stunning-guacamole.git

23  git push -u origin master
