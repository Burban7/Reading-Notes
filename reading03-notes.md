# Revisions and the Cloud


### ***Version Control System***

*************

- System that allows you to revisit versions of a file or set of files by recording changes.

- A VCS is capable of many things, including:
  - Revert a file or project to a previous version
  - Track modifications and modifying individuals
  - Compare changes
  - Easily fix mistakes in files

- A **Local VCS (LVCS)** is one database on your hard disk that stores changes to files

- A **Centralized VCS (CVCS)** is a single server storing all changes and file versions, which can be accessed by various clients.
  - Created to address the need for collaboration within a developer team on a single file or set of files

- A **Distributed VCS (DVCS)** Allows clients to create mirrored repositories that can easily be placed on the server to replace any losyt information.
  - Created to address the vulnerability of the server as a single point of failure


### ***What is Git?***

***************

- Git is a DVCS that stores data in a file system made up of snapshots.
  - Each time you commit a changed version of your project, Git creates a snapshot of the file and stores a reference to it.

- Mostly relies on local operations because most necessary information can be found in local resources.

- Every change applied to any file or directory is tracked by Git.
  - Git will always detect file corruption or loss of information while in transit

- Git is set up to minimize the possibility of irreversible damage to files.

- Files in Git can reside in three main states:
  1. **Committed**: Data is securely stored in a local database.
  2. **Modified**: File has been changed but not committed to the database.
  3. **Staged**: Flagged a file's changed version to be committed in the next snapshot.

- Git was created in 2005 by *Linus Torvalds*.

- The Git tool **`get config`** allows the setting of configuration variables that control aspects of Git's operation and look.

- To check Git settings, use the command **`git config --list`**


### ***Setting up a Git Repository***

****************

- You can create a copy of an existing Git repository from a perticular server by using the repository's URL with the command **`git clone (url)`**

- Cloning the file copies every version of all files for a project.

- You can clone a repository into a directory with another name using the command **`git clone (url) (dirname)`**


### ***Workflow***

*****************

- The local Git repository has three components:
  1. **Working Directory**: The actual files reside here
  2. **Index**: The area used for staging
  3. **Head**: Points to the most recent commit

- All files in a checked out copy of a project file are in one of two states:
  1. **Tracked** files can be modified, unmodified, or staged. These files were part of the most recent snapshot.
  2. **Untracked** files were not in the last snapshot and do not currently reside in the staging area.

- The life cycle of file status is summarized into three main parts:
  1. After editing a file, Git flags it as modified.
  2. The modified file is staged.
  3. The modified file is committed.

- To check a file's status, use the command **`git status`**

- To track a single file, use the command **`git add (filename)`**

- To track all files in a repository, use the command **`git add *`**

- To commit a file, use the command **`git commit -m`**

- To commit all changes, use the command **`git commit -a`**

- To push changes to a remote repository, use the command **`git push`**

- To stash changes, use the command **`git stash`**

- To retrieve changes you have stashed, use the command **`git stash apply`**


### ***Remote Repositories***

*******************
- Teams can use remote repositories to push information to and pull data from.

- When dealing with **cloned repositories**, Git will automatically give the name ***"Origin"*** to the server and the name ***"Master"*** to your local branch.

- Running the command **`git remote`** will show you the short names of all specified remote handles.

- Running the command **`git remote -v`** will show you allthe remote URL's next to their corresponding short names.

- To create a new remote Git repository with a short name, use the command **`git remote add (shortname) (url)`**

- To fetch/pull data that you don't already have, use the command **`git fetch (remotename)`**

- For **cloned repositories**, use the command **`git fetch origin`** to pull down any new changes that were pushed to the server since you cloned or last fetched from it.

- To push your change, use the command **`git push`**

- To remove a remote's short name, use the command **`git remote rename`**

- To remove a remote, use the command **`git remote rm`**


### ***Repository Directory***

**********************

- [Growth Mindset](https://burban7.github.io/Reading-Notes)
- [Learning Markdown](https://burban7.github.io/Reading-Notes/reading01-notes)
- [The Coder's Computer](https://burban7.github.io/Reading-Notes/reading02-notes)
