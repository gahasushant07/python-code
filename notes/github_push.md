## …or create a new repository on the command line
## echo "# python-1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/gahasushant07/python-1.git
git push -u origin main


## …or push an existing repository from the command line
git add .
git commit -m "github commit"
git push origin main

--------------------------------
Whenever you make changes:
git add .
git commit -m "your message"
git push
