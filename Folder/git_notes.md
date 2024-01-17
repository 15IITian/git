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
  
  #### Changing more older commits ->

   ##### git rebase ->
     - `git rebase --interactive commit_hash^` (^ => to include that commit also) => `edit`: to make more changes and amend it => `git rebase --continue`.
     => `reword` : to change only commit message.


#### Extra Points->
* git add -p => helps to add changes to staging area patch wise.
* git show commit_hash => show the changes


