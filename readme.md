|git branch|
Will show you a list of branches that you have. If anything is typed after 'branch', then will create a branch with that as its name.
|git checkout|
Will, when specified, swap your current branch to the one specified (assuming it exists).
|git log|
Will show the commit history of the branch you're on.
|git merge|
Will merge the specified branch's history with your current branch's.
|git init|
Starts up a Git repository within an existing directory.
|git add|
Adds a file as-is to your next commit. If a period is put in, adds every file within the branch.
|git commit -m|
After adding a message behind the -m using quotation marks, commits content that was added, and includes the message.
|git push|
Sends local commits to a remote repository branch (denoted first, so "git push remote local")
|git clone|
Retrieves an entire repository from the URL given.
|git rm|
Deletes the specified file, and sets that deletion for the next commit.
|git pull|
Merges the remote branch and its commits into the working local branch.
|git stash|
Saves the current staged changes in a 'special stack'. Adding "list" to it will list out the stack of what's stashed, adding "pop" will re-add the topmost (last-added) stash to the commit, and adding "drop" will delete the topmost stash.
{i}
Allows you to edit a file by typing into it. The [Esc] button reverts you to command mode.
{:wq}
Saves any and all changes made to a file, then quits out of the file.
{:q}
Quits out of the file. Will give a warning if any changes have been made to it prior.
{:q!}
Quits out of the file without saving.
{u}
Undoes the last change.
{U}
Undoes every change on a line, resetting it to its last save.
[cd]
Changes directory in a terminal.
[mv]
Either moves a file into a folder named, or renames a file if no folder with that name exists.
[mkdir]
Creates a new directory with the name given.
[pwd]
Prints Working Directory onto your terminal.
[ls]
Lists out files and folders.
[rm]
Deletes the specified file. Unlike the git variant, is instant and not tied to being commited.
[more]
Lists out the contents of a text file, and by certain parameters, if established.
[touch]
Creates an empty text file with the specified name.
[chmod]
Changes the permissions on a file, depending on what is put for each of the three fields, for the Owner (the first digit), the Group (the second digit), and Others (the third digit).
