# Class 3 Reading notes

### VERSION CONTROL

- VCS - Version control system - allows you to see versions to a file by recording changes
- Local VCS controls files on your hard drive
- CVCS - Centralized Version Control 
  - a single server stores all version that can be accessed by multiple people working on the same project 
- DVCS - Distributed Version Control System
  - allows clients to create mirrored repositories to avoid vulnerabilities in the storage only on one server
  - allows various simultaneous workflows 

###  WHAT IS GIT

- Git is a DVCS that stores snapshots (taken when a user submits (commits) a changed version of a project
- Git mostly relies on local operations 
  - faster, and allows work when disconnected from server
- Every change to a file is tracked
- minimizes the possibility of damage to files or file loss
- Files can reside in three states:
  - Committed - data is stored in local database
  - Modified - file has been changed but has not been committed to the database
  - Staged - Flagged a file’s changed version to be committed in the next snapshot
- Git was developed in 2005 by Linus Torvalds the chief architect of the Linux kernel 

### WORKFLOW

- Local Repository structure
  - Working Directory: The actual files reside here
  - Index: The area used for staging
  - Head: Points to the most recent commit  
- All checked out (working) files are either:
  - tracked: can be modified, unmodified or staged
  - untracked: were not in the last snapshot and not currently in the staging area
- After you edit a file, Git flags it as modified because of changes made after the previous commit.
- You stage the modified file.
- Then, you commit staged changes.   
- Check file status : `git status`
- Committing a file: `git commit -m “made change x,y,z”'
- Pushing changes to the remote repository `git push origin master`
- Stashing: if you aren't ready to commit changes but don't want to lose them
- Q: When would we use stashing instead of just committing?

### REMOTE REPOSITORIES

- remote repositories: versions of a project residing online (GitHub) or on a network
- For cloned repositories to work locally 
  - Origin: is the server they were cloned from
  - Master: is the local branch
- Seeing your remotes `git remote` - see short names of specified remote handles
- `git remote -v` view all the URLs next to their short names
