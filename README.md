## Alauddin Ansari The Wonder

### Working with GIT from terminal

* Create a new repository on GitHub.

- Create a directory on your local system
```sh
$ mkdir MyNewGitDir
``` 


- Change the current working directory to your local project.
```sh
$ cd MyNewGitDir
``` 


- Initialize the local directory as a Git repository.
```sh
$ git init
``` 

> If you are initializing fresh new project first time on your local, only then use git remote add origin otherwise skip this step 

> Copy remote repository URL fieldIn your GitHub repository, in the right sidebar, copy the remote repository URL.


- In Terminal, add the URL for the remote repository where your local repostory will be pushed.
```sh
$ git remote add origin [remote repository URL]
``` 

- Verifies the new remote URL
```sh
$ git remote -v
``` 


- Sync your existing project
```sh
$ git pull [remote repository URL]
```

- Add the files in your new local repository. This stages them for commit.
```sh
$ git add .
``` 


- Commits the tracked changes and prepares them to be pushed to a remote repository
```sh
$ git commit -m 'First commit'
``` 


- Push the changes in your local repository to GitHub.
```sh
$ git push origin master
``` 


> Enter your GitHub UserName

> Enter your GitHub Password

> :)
