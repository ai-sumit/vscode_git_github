```python
C:\VSCODE> cd C:\VSCODE\JAVA tablet

C:\VSCODE\JAVA tablet> git init
Initialized empty Git repository in C:/VSCODE/JAVA tablet/.git/

C:\VSCODE\JAVA tablet>git add .

C:\VSCODE\JAVA tablet>git commit -m "Add new folder to the repository"
[master (root-commit) e20ca87] Add new folder to the repository
 4 files changed, 33 insertions(+)
 create mode 100644 3.Selections/AdditionQuiz.class
 create mode 100644 3.Selections/AdditionQuiz.java
 create mode 100644 3.Selections/simpleifdemo.class
 create mode 100644 3.Selections/simpleifdemo.java

C:\VSCODE\JAVA tablet>git push origin https://github.com/ai-sumit/java-basics.git
fatal: invalid refspec 'https://github.com/ai-sumit/java-basics.git'

C:\VSCODE\JAVA tablet>git remote add origin https://github.com

C:\VSCODE\JAVA tablet>git push -u origin master
fatal: repository 'https://github.com/' not found

C:\VSCODE\JAVA tablet>git remote add origin https://github.com/ai-sumit/java-basics.git
error: remote origin already exists.

C:\VSCODE\JAVA tablet>git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com'

C:\VSCODE\JAVA tablet>git remote set-url origin https://github.com/ai-sumit/java-basics.git

C:\VSCODE\JAVA tablet>git push -u origin master
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (7/7), 2.32 KiB | 2.32 MiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/ai-sumit/java-basics/pull/new/master
remote:
To https://github.com/ai-sumit/java-basics.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

C:\VSCODE\JAVA tablet>
```
