Simple git commands used frequently

## **Setup & Init**


- Initialize an existing directory as a Git repository\
```git init```

- Retrieve an entire repository from a hosted location via URL\
```git clone [url]```




## **Stage & Snapshot**


- Show modified files in working directory, staged for your next commit
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
```git commit -m “[descriptive message]”```

## Branches
<hr>

- Lists **all local branches**.\
```git branch```

- List **remote and local branches**.\
```git branch -a```

- Create a local branch and switch to it.\
```git checkout -b branch_name```

- Switch to an existing branch.\
```git checkout branch_name```

- Push branch to remote.\
```git push origin branch_name```

- Rename current branch.\
```git branch -m new_name```

- Delete a local branch.\
```git branch -d branch_name```

- Delete a remote branch.\
```git push origin :branch_name```

