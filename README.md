- Cloning a repository clone the repository onto your computer (different than downloading it directly)
``
    ```
    git add .                                                        
    ```
    2. take added changes and prepare them for pushing
    ```
    git commit -m "<commit message>"    
    ```
    3. integrates changes into online repository
    ```
    git push origin <name of branch>         
    ```
  
- Merge branches
    1. make sure changes are pushed on both branches
    ```
    git checkout <branch you want to update>
    git merge origin <other branch>
    ``` 
    
Merge Conflicts: \
You are trying to push your changes and you get this error: \
![Push Error](push.png)

First pull:
```
git pull
```

You should get this: \
![Merge Conflict](merge_conflict.png)

Why use branches? / How to use branches effectively?

Main branch - Should always be functional
Feature branch - Meant for development
