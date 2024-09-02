# ISEC6000-SecureDevOps
## Some steps to set up the git repo.
install git:
sudo apt-get install git

Configuration:
git config --global user.name "Name"
git config --global user.email “email@example.com"

create one separate directories:
mkdir securedevops

git init

To add files:
git add .

To commit the added file:
git commit -m "Initial commit"

Link the Local Repository to the Remote Repository:
git remote add origin <repos-url>

git push -u origin main
