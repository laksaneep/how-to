# Work with git


### Case 1 : Want to push local project to github
1. Add .git in local project
   ```
   git init
   ```
2. Create your repository on github
3. Add remote repository to your project
   ```
   git remote add origin https://github.com/OWNER/REPOSITORY.git
   ```
4. Check your remote repo
   ```
   git remote -v
   ```
5. Create branch in local project
   ```
   git branch -M main (git branch -M <branch>)
   ```
6. Add all your changed code to 'staged'
   ```
   git add .
   ```
   or
   ```
   git add folder-name filename.txt 
   ```
8. Commit to your _local_
   ```
   git commit -m 'message you want to commit'
   ```
9. Push your commit to your _Remote Repository_
   ```
   git push -u origin main (git push -u origin <branch>)
   ```

### Case 2 : Want to clone remote repo to your project
1. Clone remote repo to local project 
   ```
   git clone https://github.com/OWNER/REPOSITORY.git
   ```
2. Check Is there any update?
   ```
   git fetch
   ```
   ```
   git pull
   ```
3. Start write code with others
4. Add all your changed code to 'staged'
   ```
   git add .
   ```
   or
   ```
   git add folder-name filename.txt 
   ```

   *** if need to clear all files/folder in 'staged'
   ` git reset `
   
7. Commit to your _local_
   ```
   git commit -m 'message you want to commit'
   ```
8. Push your commit to your _Remote Repository_
   ```
   git push -u origin main (git push -u origin <branch>)
   ```

### Manage branch

1. Check out existing branch
   ```
   git checkout <branch name>
   ```
2. Create new branch
   ```
   git checkout -b <branch name>
   ```
3. Check all branchs
   ```
   git branch --list
   ```

### Check status of files
   ```
    git status
   ```

### Delete local repo in your project
   ```
   rm -rf .git
   ```
