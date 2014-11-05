To initialize a local repo: 
1. create the remote repo online without the readme
2. navigate to the directory to be published
3. git init
4. git add .
5. git commit -m "the message"
6. git remote add origin <remote repo url>
7. git push origin master


git remote -v 
to verify existing remote


git remote set-url origin https://github.com/rickydo/my_repo.git 
if you cannot write to remote repo but remote repo exists