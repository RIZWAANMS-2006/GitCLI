cd "/media/rizwaan/Shared Disk/Coding/GitCLI"

git --version

git config --global user.name "Rizwaan"
git config --global user.email "your@email.com"
git config --global --list

git init

ls -la

git status

git add .

git add README.md

git commit -m "Initial commit"

git log

git log --oneline

git diff

git branch

git branch -M main

git remote -v

git remote add origin https://github.com/YOUR_USERNAME/GitCLI.git

git push -u origin main

git push

git pull

git clone https://github.com/YOUR_USERNAME/GitCLI.git

sudo apt update
sudo apt install git

sudo apt install gh

gh --version

gh auth login

gh auth status

gh repo create GitCLI --public --source=. --remote=origin --push

gh repo view --web
