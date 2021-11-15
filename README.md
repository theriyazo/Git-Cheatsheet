# GitHub CheatSheet by RiyazAhamad(theriyazo)

Created: November 6, 2021 1:17 AM
### Materials: [src_1](https://git-scm.com/docs/git), [src_2](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [x] Reviewed

## Git Commit History [#](https://git-scm.com/docs/git#Documentation/git.txt-ahrefdocsgit-loggit-log1a) :

<aside>
💲  git log 

</aside>

- Going back to a commit [#](https://git-scm.com/docs/git#Documentation/git.txt-ahrefdocsgit-checkoutgit-checkout1a)
    
    <aside>
    💲  git checkout <hash-code> 
    
    </aside>
    

# Most Used Git Commands

## Rename master to main [#](https://www.git-tower.com/learn/git/faq/git-rename-master-to-main)

<aside>
💲  git branch -m master main 

</aside>

## List hidden files

<aside>
💲  ls -a 

</aside>

## Complete Log

<aside>
💲  git log 

</aside>

- gives the <hashNumber> and details
- to exit git log → `q` or `z`

## Logs changes

<aside>
💲  git add <file> 

</aside>

## Adding commit message

<aside>
💲  git commit -m "<message>" 

</aside>

## Logs commit

<aside>
💲  git commit -m <file> 

</aside>

## current tree status

<aside>
💲  git status 

</aside>

## vi editor

- enter vi
    
    <aside>
    💲  vi 
    
    </aside>
    
- exit vi editor
    
    <aside>
    💲 [ESC] : x
    
    </aside>
    

## Files

- To create file
    
    <aside>
    💲  touch <file> 
    
    </aside>
    
- To look inside file
    
    <aside>
    💲  cat <file> 
    
    </aside>
    
- Remove/Delete file
    
    <aside>
    💲  rm -rf <file> 
    
    </aside>
    

## Staging

- Adding files to a particular file
    
    <aside>
    💲  git add <file> 
    
    </aside>
    
- Adding all the files
    
    <aside>
    💲  git add . 
    
    </aside>
    
- To add all files with the particular extension
    
    <aside>
    💲  git add *.<fileExtension>
    
    </aside>
    
- Un-stage particular commit changes
    
    <aside>
    💲  git reset <hashNum> 
    
    </aside>
    
- Removing file from stage
    
    <aside>
    💲  git restore - - staged <file> 
    
    </aside>
    
    <aside>
    💲  git rm - - cached <file> 
    
    </aside>
    

## Stash

- Adding files to  Stash
    
    <aside>
    💲  git stash 
    
    </aside>
    
    - adds all the files to stash
- Adding message to a stash
    
    <aside>
    💲  git stash save "<message>" 
    
    </aside>
    
- Pop the Stash files
    
    <aside>
    💲  git stash pop 
    
    </aside>
    
- To clear the stash
    
    <aside>
    💲  git stash clear 
    
    </aside>
    
- To list stash
    
    <aside>
    💲  git stash list 
    
    </aside>
    
- To Pop particular files
    
    <aside>
    💲  git stash pop stash@{indexNo} 
    
    </aside>
    

## Remote Repository

- Adding remote Repo to local repo
    
    <aside>
    💲  git remote add origin <https://gitRepoURL.git> 
    
    </aside>
    
- To check attached URLs
    
    <aside>
    💲  git remote -v 
    
    </aside>
    
- To push changes to remote Repo
    
    <aside>
    💲  git push origin <HEAD Branch> 
    
    </aside>
    
    - for main or master branch it will be `git push origin main` or `git push origin master`
    - for branch → `git push origin <branchName>`
- To pull remote repo commits/changes
    
    <aside>
    💲  git pull 
    
    </aside>
    
- To remove remote repo URL
    
    <aside>
    💲  git remove remote origin 
    
    </aside>
    
- To update remote repo
    
    <aside>
    💲  git remote set-url origin <newRemoteRepoURL.git> 
    
    </aside>
    
- To add add Upstream (forked repo URL)
    
    <aside>
    💲  git remote add upstream <URL> 
    
    </aside>
    
- To check remote repo
    
    <aside>
    💲  git remote 
    
    </aside>
    
- To clone remote repo
    
    <aside>
    💲  git clone <repoURL> 
    
    </aside>
    

## Branching

- To Create new branch
    
    <aside>
    💲  git branch <branchName> 
    
    </aside>
    
- To Switch to particular branch
    
    <aside>
    💲  git checkout<branchName> 
    
    </aside>
    
- To Create new branch and switch to it
    
    <aside>
    💲  git checkout -b <branchName> 
    
    </aside>
    
- Merge the current branch
    
    <aside>
    💲  git merge <branchName> 
    
    </aside>
    
    - make sure you've switched to the branch you want the other branch to merge with.

## Basic git bash commands

- To move previous directory
    
    <aside>
    💲  cd .. 
    
    </aside>
    
- To move to home directory
    
    <aside>
    💲  cd ~ 
    
    </aside>
    
- To move to root
    
    <aside>
    💲  cd / 
    
    </aside>
