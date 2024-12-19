How to configure Git on Ubuntu and add ssh key to github
https://dev.to/kellycarvalho/how-to-configure-git-on-ubuntu-and-adding-ssh-key-to-github-4h5d

---------------------------------------------------------------------------------------------
…or create a new repository on the command line
echo "# t" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:YuvrajBhupati/t.git
git push -u origin main

--------------------------------------------------------------------------------------------
…or push an existing repository from the command line
git remote add origin git@github.com:YuvrajBhupati/t.git
git branch -M main
git push -u origin main
