1.  `git`

  Check to see if git is installed on your machine

2.  `cd`

  `cd` will bring you to your root directory

3.  `ls -a`

  List folders (`ls`) including hidden folders and files (`-a`)

4.  `mkdir .ssh`

5.  `cd .ssh`

6.  `ls -alt`

  Check for `id_rsa` and `id_rsa.pub` files

7.  `ssh-keygen`

  Generate ssh keys

8.  `cat id_rsa.pub`

  Copy ssh key and paste into ssh section of your github account page

9.  `git config --global user.name "Sarah Kurisu"`

  Use your name

10.  `git config --global user.email "sarah.kurisu@gmail.com"`

  Use same email conneceted to your github account

11.  `git config --list`

  Double check that all information is correct.  If there are any errors, rerun command in step 11 or 12

12.  `cd` takes us back to root directory

---

13.  `mkdir development`

14.  `cd development`

15.  `git init`

  Make git available for use in this directory

16.  `touch README.md`

  Creates a file called 'README' in markdown (.md)

17. `open -e README.md`

  Open readme file in textedit and type in anything (your name, a sentence, whatever you like!)

18.  `git add README.md`

  Stage your file

19.  `git commit -m "initial commit"`

  Commit messages are concise and give an idea to what changes/updates were made

20.  In github UI, create a new repository.  Add via ssh

21.  `git remote add origin git@github.com:skurisu/stunning-guacamole.git`

22.  `git push -u origin master`
