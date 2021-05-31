## Github Workshop

- cloning a repository clone the repository onto your computer (different than downloading it directly)
  1. git clone <link>

- switch to different branch
  1. if creating a new branch - git checkout -b"<name of branch>"
  1. if switching to a branch that already exists - git checkout <name of branch>"

- update local version of repository
  1. git pull origin <name of branch>

- push changes from local to online repository
  1. git add .                                                        adds all changes
  2. git commit -m "<commit message>"    take added changes and prepare them for pushing
  3. git push origin <name of branch>         integrates changes into online repository

- merge branches
  1. make sure changes are pushed on both branches
  2. git checkout <branch you want to update>
  3. git merge origin <other branch>
