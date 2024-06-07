## Practicing Git Commands 
## to put this file in Git 
#### Repository we need to GIT initialize on the terminal. it will initialise the folder as repository 
# …or create a new repository on the command line
echo "# PracticeGIT" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main 
# Main is on local device
git remote add origin https://github.com/ProfVerma/PracticeGIT.git
# remote origin is repository on GitHub
git push -u origin main
# …or push an existing repository from the command line
git remote add origin https://github.com/ProfVerma/PracticeGIT.git
git branch -M main
git push -u origin main
