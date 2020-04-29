# vfrsoft-maven-archetype-sample01

To generate `.gitignore` run:

``` bash
wget https://www.gitignore.io/api/visualstudiocode,sublimetext,netbeans,maven,linux,java,intellij+iml,intellij+all,intellij,eclipse --output-document=".gitignore"

sed -i -e 's/!\.vscode/# !\.vscode/g' ./.gitignore
```
