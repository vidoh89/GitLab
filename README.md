This repository focuses on different Git concepts and practices. It is meant to provide a dedicated repo for Git projects and challenges I face.This will serve as a self kept diary of my Git journey .

10/18/2023
Knowledge check-Git untracked and tracked status.
Refers to files that have been tracked and or staged and files that are recognized however they are not being tracked.

commands and flags(shorthand):

git add --all(git add -A) "adds all files to the staging environment."

git commit -m "Adding commits keeps track of changes.It's somewhat of a savepoint.This would be the point to revert back to to make changes.(-m) adds the message to the commit.Messages should outline any changes and or updates made to the application."

git config user.name "name" ---Sets the user name for the current repository.
10/19/2023
Git use:
-Tracking code changes
-Tracking who made changes
-Coding collaborations

=Manages projects with Repositories
=Clone projects to work on locally
=control and track changes with staging and committing
=Branch and Merge to allow work on different parts of a project
=Pull the latest version of a project to a local copy
=Push local updates to a main project

=CMD
-git config --global user.name "name"
This uses the global flag to set user name and also can set email
for all repos.
``
-git restore --staged <file.name>--restores a staged file to previous state.
``

==Note: Navigating git via GitBash has the same basic commands as powershell.I was confused about the navigation but now that is understood.
=endNote
CMD
 -git config --global --add safe.directory <PATH>
 This will allow access to a directory via GitBash.
 
 Note:There is a difference in navigation between GitBash and powershell
 cd.. in powershell will revert to previous folders.cd .. in gitbash has the same effect. However there is a space in gitbash(cd ..)vs powershell(cd..).
 ``
 CMD
 -git status --short(returns more of a compact overview of changes)
 --short status flags--
 ?? -untracked files
 A - Files added to stage
 D - Deleted files
 ``
 CMD
 -git commit -a -m (makes commit while skipping the staging process).
 CMD
 -git log (returns meta data of changes and who made theme)
 CMD
 -git help --all (gives access to all git commands press q to escape browser command list.)
 CMD
 -git command -help(this will list meta data about the specified command ie command would be an actual command-commit,add,etc)



