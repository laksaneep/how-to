# Work with git

### Create and add your remote repo

1. Create your repository on github
2. Add remote repository to your project
   ```
   git remote add origin https://github.com/OWNER/REPOSITORY.git
   ```
3. Check your remote repo
   ```
   git remote -v
   ```

### Update your local repo

1. Check different between local and remote repo
   ```
   git fetch
   ```
2. Pull your remote repo to your local
   ```
   git pull
   ```

### Push your code

1. Add all your changed code to 'staged'
   ```
   git add .
   ```
2. Commit to your _local_
   ```
   git commit -m 'message you want to commit'
   ```
3. Push your commit to your _Remote Repository_
   ```
   git push -u origin master
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

    git status
