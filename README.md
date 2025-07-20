# Intialise git
    - git init
# Add Untracked files into Staging Area 
    - git add . or git add <filename>
# Shown the working tree status
    - git status
# Unstage or Untrack The File
    - git rm --cached <filename>
# Saves the changes or Take Snapshot - commit
    - git commit -m "message"
# Link Your local git repo to remote git repo hosted in online
    - git remote add origin <url>
# Managing Branches
    - git branch (List all)
    - git branch <branch-name> (Create new branch)
    - git switch <branch-name> (Switch the branch)
        or
    - git checkout <branch-name> (Switch the branch)

# Move master to main -  (Rename Branch Forcefully)
    - git branch -M main
            or
    - git branch --move main (or) git branch --force main 
# Push local repo changes to remote repo hosted in online
1. Push main to origin AND set up a tracking relationship for future 
   pushes/pulls. Use it for the initial push of a new branch.
         `git push -u origin main`
2. Push main to origin. Use it for subsequent pushes once the tracking 
   relationship is established.
        `git push origin main`
3. Forcefully overwrite the remote branch history with your local   
   branch's history. Use it with extreme  caution, mainly on 
   brancheswhere you are the sole contributor or after carefully 
   coordinated history rewriting.
        `git push --force`
4. Push a specific local branch to a remote branch with the same name 
   on origin. This is the standard practice for pushing work on separate branches.
        `git push origin <feature/branch>`
   
          


