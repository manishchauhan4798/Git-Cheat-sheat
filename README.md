# Git-Cheat-sheat
**Install GIT**

Github provides desktop clients that include a Graphical user interface for the most common Repository actions and an automatically updating command line edition of Git for Advance Scenarios.

**Github for Windows**
https://windows.github.com 
**Github For Mac**
https://mac.github.com

Git distributions for **Linux** and **POSIX** systems are available on the offical **GITSCM web site**.

**Git for all platforms**
http://git-scm.com

## CONFIGURE TOOLING
**_CONFIGURE USER INFORMATION FOR ALL LOCAL REPOSITORIES_**

**$ git config --global user.name "[name]"**

*sets the name you want attached to your commit transcations*

**$ git config --global user.email "[email address]"**

*sets the email you want attached to your commit transcations*

**$ git config --global color.ui auto**

*Enables Helpful colorization of commmand line output*

## CREATE REPOSITORIES
**_start a new repository or obtain one from an existing URL_**

**$ git init [project-name]**

_create a new local repository with the specified name_

**$ git clone [url]**

_Download a project and its entire version history_

## MAKE CHANGES
**_Review edits and Craft a commit transcation_**

**$ git status**

_Lists all new or modified files to be committed_

**$ git diff**

_Shows file differences not yet staged_

**$ git add[file]**

_Snapshots the file in preperation for versioning_

**$ git diff --staged**

_Shows file differnece between staging and the last file version_

**$ git reset [file]**

_Unstages the file,but preserve its contents_

**$ git commit -m "[descriptive message]"**

_Records File snapshots permanently in version history_

## GROUP CHANGES
**_name a series a commits and combine completed efforts_**

**$ git branch**

_lists all local branches in the current repository_

**$ git branch [branch-name]**

_Create a new branch_

**$ git checkout [branch-name]**

_Switches to the specified branch's history into the current branch_

**$ git merge[branch]**

_Combines the specified branch's history into the current branch_

**$ git branch -d [branch-name]**

_Deletes the specified branch_

## REFACTOR FILENAMES
**_Relocate and remove versioned files_**

**$ git rm [file]**

_Delets the file from the working directory and stages the deletion_

**$ git rm --cached [file]**

_Removes the file name and prepares it for commit_

**$ git mv [file-original][file-renamed]**

_change the file name and prpeares it for the commit_

## SUPRISE TRACKING
**_Exclude temporary files and path_**

**_*.log build/temp-*_**

_A text file named _.gitignore_ suppresses accidental versioning of files and paths matching the speciifed patterns.

**$ git ls-files --others --ignored --exclude-standard**

_Lists all ignored files in this project_

## SAVE FRAGMENTS
**_Shelve and restore incomplete changes_**

**$ git stash**

_Temporarily stored all modified tracked files_

**$ git stash pop**

_Restores the most recently stashed files_

**$git stash list**

_List all stashed changesets_

**$ git stash drop**

_Discard the most recently stashed changeset_

## REVIEW HISTORY
**_Browse and inspect the evolution of project files_**

**$ git log**

_lists version history for the current branch_

**$ git log --unfollow [file]**

_lists version history for a file,including renames_

**$ git diff [first-branch]...[second-branch]**

_Shows content differences between two branches_

**$ git show[commit]**

_Output metadata and content changes of the specified commit_

## REDO COMMITS
**_Erase mistake and craft replacement history_**

**$ git reset[commit]**

_Undoes all commits after[commit],preserving change locally_

**$ git reset --hard [commit]**

_Discard all history and change back to specific commit_

## SYNCHRONIZE CHANGES
**_Register a repository bookmark and exchange version history_**

**$ git fetch [bookmark]**

_Download all history from the repository bookmark_

**$ git merge[bookmark]/[branch]**

_Combines bookmarks branch into current local branch_

**$ git push [alias] [branch]**

_Uploads all local branch commits to the Github :octocat:_

**$ git pull**

_Download bookmark history and incorporate changes_

# THE END 
