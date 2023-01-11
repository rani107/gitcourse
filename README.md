# Revert changes from working directory 
git restore  filename or git checkout filename 

# Revert changes from staging area 
git restore --staged filename ( revert changes from staging area to working directory)
git restore file name ( revert changes from working directory )

# Revert changes from local repository 
git reset HEAD~  ( to revert changes from local repo to working directory)
git restore file name ( to revert chages from working directory )

# Revert changes from remote repository
we dont have direct way to do this .
