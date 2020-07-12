# basic-git-commands
Here is the flow I normally use in git, the most used commands.


## Clone repository

```
1. git clone https://github.com/username/yourproject.git
```


## Merge develop to master

```
1. git checkout master 
2. git merge develop
3. git push -u origin master
```

## Creating tags

```
1. git tag <tagname> 

If you want to include a description with your tag, add -a to create an annotated tag:
  
    git tag <tagname> -a with description
    
2. git push origin --tags

Or if you just want to push a single tag:

  git push origin <tag>
  ```
  
  ## Deleting tags
  
  ```
1. git push --delete origin tagname
  ```
  
  ## Clean changes
  
  ```
  1. git checkout --
  2. git clean -f -d
  3. git reset HEAD
  4. git log --stat
  ```
  
  
```
