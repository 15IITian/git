### Git stash -> 
     * bring to stage area ->  then stash 

### Git branching ->
     * do not directly commit on main branch
     * Whenever working on new feture , bug etc ->  do not work in main branch

### Upstream ->
     * From where We fork the project directory.

### Origin ->
    * repository which I have access to.
    * eg -> Forked account 

### Important point->
    * For working on every new feature , bug etc -> make new branch for it .
    * Do not directly commit in master branch
### 1 Branch allows only 1 pull requests -> then after commits will added into it.
 *  ## **For working on different fetures -> create seperate branches for it => create sepearte pull requests related to it.**  

* eval $(ssh-agent)
* ssh-add ~/.ssh/id_ed25519

## Rewritting history ->
 #### git commit --amend -> 
   - to make changes in the latest commit -> commit + staged_changes = new commit 
   - if no staged_changes =0 -> edit commit's message only
   - **--no-edit** flag -> amend commits without changing its commit message. 
  
  #### Changing older or multiple commits->

  ##### git rebase ->
  - -i 


#### Extra Points->
* git add -p => for more informative while also staging changes
* git show commit_hash => show the changes
