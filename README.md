# vfrsoft-maven-archetype-sample01

Setup commands:

``` bash
wget https://www.gitignore.io/api/visualstudiocode,sublimetext,netbeans,maven,linux,java,intellij+iml,intellij+all,intellij,eclipse --output-document=".gitignore"

sed -i -e 's/!\.vscode/# !\.vscode/g' ./.gitignore

git init
git config user.email "dholtdev@gmail.com"
git add --all
git status
git commit -m "initial check-in"
```
