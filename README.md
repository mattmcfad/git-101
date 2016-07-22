# Git 101

## creating a new project

```

git init

```


## remotes

### check your remotes

```

git remote -v

```

### adding a remote

```

git remote add origin https://github.com/user/repo.git

```

* remotes refer to the repository


## commits

### adding files to commits

```

git add filepath/filename.whatever

```

### batch adding all the files!

```

git add -A

```

### creating the commit and adding the message

```

git commit -m "my first commit, this is the commit message that shows up on github"

```

### adding all the files and a commit messsage at the same time

```

git commit -am "added all files yolo and this is the commit message"

```


## Views from the CLI

### view the status of your git

```

git status

```

### view your commits 

```

git log

```

## pushing your commits

```

git push remoteName branchName

```

`eg: git push origin master`


## branches

### creating branches

```

git checkout -b newbranchname

```

### switching branches

```

git checkout branchName

```

### quick switch to the last branch you were on

```

git checkout -

```

### Getting changes from the remote

```

git fetch remoteName

```

* grabs all code & new branches, basically gets everything from remote


### pulling from a specific branch

```

git pull remoteName branchName

```

* make sure you're on the same branch

`e.g. git pull origin master` to get lastest changes.

