README.md
SI'BEN PSEUDO CODE FOR GIT SOLUTION

1. GIT task: Repo-session

Solutionwheels

Create a new directory called 0x01-git in your alx-pre_course repo. Make sure you include a non empty README.md in your directory: at the root of your repository alx-pre_course AND in the directory 0x01-git And important part: Make sure your commit and push your code to Github - otherwise the Checker will always fail..

ANSWER:

follow this codes step by step

cd alx-pre_course (enter)

mkdir 0x01-git (enter)

cd 0x01-git (enter)

echo “my second commit”>README.md (enter)

cd .. (enter)

git add . (enter)

git commit -m 'My second commit' (enter)

git push origin main (enter)

 

(Now check your code)

2. GIT task: Coding fury road

Solutionwheels

For the moment we have an empty project directory containing only a README.md. It’s time to code! Create these directories at the root of your project: bash, c, js Create these empty files: c/c_is_fun.c js/main.js js/index.js Create a file bash/alx with these two lines inside: #!/bin/bash and echo "ALX" Create a file bash/school with these two lines inside: #!/bin/bash and echo "School" Add all these new files to git Commit your changes (message: “Starting to code today, so cool”) and push to the remote server.

ANSWER: 

 

cd 0x01-git (enter)

mkdir bash (enter)

mkdir c (enter)

mkdir js (enter)

ls (enter) – this to check if the directories have been created

 

 

touch c/c_is_fun.c (enter)

touch js/main.js (enter)

touch js/index.js (enter)

cd c (enter)

ls (enter)

cd .. (enter)

 

cd bash (enter)

echo ‘#!/bin/bash’ >alx (enter)

echo “ALX” >>alx (enter)

 

 

echo ‘#!/bin/bash’>school (enter)

echo “School”>>school (enter)

cd .. (enter)

 

git add . (enter)

 

 

git commit -m 'Starting to code today, so cool' (enter)

 

 

git push (enter)

Check your code

3. GIT task: Collaboration is the base of a company

Answer: 

git checkout -b update_script (enter)

 

cd bash

 

touch 98 (enter)

 

 

echo ‘#!/bin/bash’ >alx (enter)

echo “ALX School” >>alx (enter)

 

 

echo ‘#!/bin/bash’>school (enter)

echo “The school is open!”>>school (enter)

 

 

cd .. (enter)

git add . (enter)

git commit -m “My personal work” (enter)

 git push --set-upstream origin update_script (enter) – to push the branch to the main)

 

 

git checkout main (enter)

 

 

 

cd bash (enter)

 

echo ‘#!/bin/bash’ >alx (enter)

echo “ALX School is so cool!” >>alx (enter)

 

 

cd .. (enter)

 

rm -rf js (enter)

 

 

git add . (enter)

git commit -m 'Hot fix'

 

git push

4. Collaboration: be up to date

ANSWER:

Go to github.com, enter your alx-pre_course Repository

Double tap on 0x01-git

Click on the README.md file below and click on the edit button. Change the content and commit it

 

Get all changes of the main branch locally (i.e. your README.md file will be updated)

Go to git bash, use the command

git pull (enter)

 

 

Create a new file up_to_date at the root of your directory and in it, write the git command line used

echo “git pull”> up_to_date  (enter)

 

Add up_to_date to git, commit (message: “How to be up to date in git”), and push to the origin

git status (enter) to check the status of your work

git add . (enter)

git status (enter) to check the status of your work if the previous works has been added.

git commit -m “How to be up to date in git” (enter)

git push

5. GIT task: HAAA what did you do???

Solution

$ cd alx-pre_course

 

~/alx-pre_course (main)

$ git merge update-script

merge: update-script - not something we can merge

 

~/alx-pre_course (main)

$ git merge update_script

Already up to date.

 

~/alx-pre_course (main)

$ git commit –m  “Cool, all my changes will be now part of the main branch, ready to be deployed!”

bash: !”: event not found

 

~/alx-pre_course (main)

$ git commit -m  'Cool, all my changes will be now part of the main branch, ready to be deployed!'

On branch main

Your branch is up to date with 'origin/main'.

 

nothing to commit, working tree clean

 

~/alx-pre_course (main)

$ git add .

 

 

 ~/alx-pre_course (main)

$ git push

Everything up-to-date

6. Never push too much

Answer:

 ~/alx-pre_course (main)

$ cd 0x01-git (enter)

 

 ~/alx-pre_course/0x01-git (main)

$ echo "~">.gitignore (enter)

 

 ~/alx-pre_course/0x01-git (main)

$ cat .gitignore (enter)

~

 

 ~/alx-pre_course/0x01-git (main)

$ git add . (enter)

 

 

 ~/alx-pre_course/0x01-git (main)

$ git commit -m "~" (enter)

 

 ~/alx-pre_course/0x01-git (main)

git push (enter)

