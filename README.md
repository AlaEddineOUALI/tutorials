#Tuto Git
git config --global user.email "alaeddine.ouali.01@gmail.com"
git config --global user.name "Ala Eddine OUALI"

# Init Depot
# dans bash
git init
#git remote add origin URL_SSH_REPO
git remote add origin git@github.com:AlaEddineOUALI/tutorials.git

git commit -m "git commit exemple"
## create branch 
git checkout -b BRANCH_NAME