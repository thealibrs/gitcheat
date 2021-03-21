<img src="https://i.hizliresim.com/fplaXz.png" alt="" width="800" height="350">


## **Setup & Init**

- Initialize an existing directory as a Git repository\
```git init```

- Retrieve an entire repository from a hosted location via URL\
```git clone [url]```



## **Stage & Snapshot**

- Show modified files in working directory, staged for your next commit\
```git status```

- Add a file as it looks now to your next commit (stage)\
```git add [your_file]```

- Unstage a file while retaining the changes in working directory\
```git reset [your_file]```

- Difference of what is changed but not staged\
```git diff```

- Difference of what is staged but not yet commited\
```git diff --staged```

- Commit your staged content as a new commit snapshot\
```git commit -m “[descriptive message]”```

## **Branch & Merge**

- List your branches. a * will appear next to the currently active branch\
```git branch```

- Switch to an existing branch.\
```git checkout branch_name```

- Create a new branch at the current commit\
```git branch [branch-name]```

- Create a local branch and switch to it.\
```git checkout -b branch_name```

- Push branch to remote.\
```git push origin branch_name```

- Switch to another branch and check it out into your working directory\
```git checkout```

- Merge the specified branch’s history into the current one\
```git merge [branch]```

- Rename current branch.\
```git branch -m new_name```

- Delete a local branch.\
```git branch -d branch_name```

- Show all commits in the current branch’s history\
```git log```


## **Share & Update**

- Add a git URL as an alias\
```git remote add [alias] [url]```

- Merge a remote branch into your current branch to bring it up to date\
```git merge [alias]/[branch]```

- Transmit local branch commits to the remote repository branch\
```git push [alias] [branch]```

- Fetch and merge any commits from the tracking remote branch\
```git pull```



