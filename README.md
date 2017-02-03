# git-questions
Git interview questions

1)How would you install git?
sudo apt-get install git(Ubuntu)

2)How to setup configurations in git?
git config --global user.name "Darshan Hegde"
git config --global user.mail darshanhegde@github.com


3)How to create a new repo?
git init(Creates a repo without a name and it has .git folder) 
or
git init "filename"


4)How to check the status in GIT?
git status

5)How to move the files to staging area?
git add filename
git status

If you want to move the whole folder then 
git add -A

6)How to commit the files in GIT?
git commit -m "Initial Commit"

