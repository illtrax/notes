## GitHub Cheatsheet

Create a new repository on the command line.

```` console
echo "# weather" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/[USER_NAME]/[REPO_NAME].git
git push -u origin master
````

Push an existing repository from the command line.

```` console
git remote add origin https://github.com/[USER_NAME]/[REPO_NAME].git
git push -u origin master
````