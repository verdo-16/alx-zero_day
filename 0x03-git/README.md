0 0-create an account on GITHUB

0 1-create a personal access token on Github

0 2-update your profile on the intranet

0 3-create your first repository

0 4-open the sandbox

0 5-clone your repository
git clone

6 -create the README.md and push the modifications.
cd alx-pre_course
echo 'My first readme' > README.md

-update your git identity
git confit --global user.email "you@example.com"
git config --global user.name "Your Name"

-push code
git add .
git commit -m 'My first commit'
git push
paste token for password

1 -create a new directory called 0x01-git
cd alx-pre_course
mkdir 0x01-git
cd 0x01-git
echo 'Some text for this read me' > README.md
git add .
git commit -m 'My second commit'
git push

2 -coding fury road
cd alx-pre_course
cd 0x01-git
mkdir bash
mkdir c
mkdir js
cd c
touch c_is_fun.c
cd ..
cd js
touch main.js
touch index.js
cd ..
cd bash
echo '#!/bin/bash'> alx
echo "ALX" >> alx
echo '#!/bin/bash'> school
echo "School">> school
git add .
git commit -m 'Starting to code today, so cool'
git push

3 -collaboration is the base of a company
cd alx-pre_course
cd 0x01-git
git checkout -b update_script
cd bash
touch 98
echo "ALX School"> alx
echo "The school is open!"> school
git add .
git commit -m 'My personal work'
git push

git checkout master
cd 0x01-git
cd bash
echo "ALX School is so cool!" >alx
cd ..
rm -r js
git add .
git commit - 'Hot fix'
git push

4 -Collaboration: be up to date
update README.md on github
cd alx-pre_course
cd 0x01-git
git pull
echo 'git pull' > up_to_date
git add .
git commit -m 'How to be up to date in git'
git push

5 -haaa what did you do??
cd alx-pre_course
git merge update_script
git merge update_script
git add .
git commit -m 'Cool, done'
git push

6 -never push too much
cd alx-pre_course
cd 0x01-git
echo "~"> .gitignore
cat .gitignore
git add .
git commit -m "~"
git push
