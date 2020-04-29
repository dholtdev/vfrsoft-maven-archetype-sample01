# vfrsoft-maven-archetype-sample01

Example setup commands:

*First create dholttrain/chegg-sam-career-fair-organizer repo in github.*

``` bash
wget https://www.gitignore.io/api/visualstudiocode,sublimetext,netbeans,maven,linux,java,intellij+iml,intellij+all,intellij,eclipse --output-document=".gitignore"

sed -i -e 's/!\.vscode/# !\.vscode/g' ./.gitignore

echo "# chegg-sam-career-fair-organizer" > README.md
echo "" >> README.md

git init
git config user.email "dholtdev@gmail.com"
git add --all
git status
git commit -m "initial check-in"

git remote add origin git@github.com:dholttrain/chegg-sam-career-fair-organizer.git
git push -u origin master

git push
git pull
git stash list
git status
```
