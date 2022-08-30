# [Class 3 Reading Notes](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#7_2)

###### [Return to Home](https://sethppierce.github.io/reading-notes)

## Version control

Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes.
Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes.

**Types**
- Local Version Control- A Local VCS entails one database on your hard disk that stores changes to files.
- Centralized Version Control(CVCS)- This system entails a single server storing all changes and file versions, which can be accessed by various clients.
- Distributed Version Control(DVCS)- addresses the major vulnerability of the CVS: the server as a single point of failure. creates mirrored repositories. 

## So, What is Git?

- Snapshots- Git is a DVCS that stores data in a file system made up of snapshots. Every time you save a new verison(commit) GHit maes a snapshot of the file.
- Local Operations- git uses local resources eliminating the need to fetch information from a server, allowing you to work offline.
- Tracking Changes- Every single change applied to a file is tracked by Git, will always detect file corruption or loss of information.
- States- Files in Git can reside in three main states: committed, modified and staged.
- Committed- Data is securely stored in a local database
- Modified- File has been changed but not committed to the database
- Staged- Flagged a file’s changed version to be committed in the next snapshot

## Workflow

### Local repository Structure

**The local Git repository has three components:**
- Working Directory: The actual files reside here.
- Index: The area used for staging
- Head: Points to the most recent commit

![](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

## Saving Changes

***All files in a checked out (or working) copy of a project file are either in a tracked or untracked state.***

Tracked -Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.
Untracked- Untracked files were not in the last snapshot and do not currently reside in the staging area.

### Check File Status
To determine the state of files, utilize the git status command: `git status`

### Tracking and Staging a New File

Single File- Track one file only by using the following format: `git add filename`

All Files- Track all files in a repository by using the following command:`$ git add *`

### Committing a File
After staging one or multiple files, you should commit the changes and record what you did within the commit message:

`$ git commit -m “made change x,y,z”`

Committing All Changes

`$ git commit -a`

### Pushing Changes
Next, you would push changes to a remote repository.

**Example:**

`$ git push origin master`
> This command pushes changes from the local “master” branch to the remote repository named “origin”.
>For cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local repository. However, these names can be changed by the user
