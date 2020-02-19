# Week 1 notes
## Git
<b>Git</b> - a version control system used by developers

<b>Github</b> - one of a number of remote VC hosts. Others include Bitbucket and GitLab.

- <b>git init</b> - Used at the beginning of the project to create a git repo
- <b>git status</b> - Used to see the current status of the git repo
- <b> git add</b> - Used to add a file to the repo, most commonly in conjunction with the . modifier to select all files
- <b>git commit</b> - Used to commit changes to the log. Requires a -m modifier with a common sense description of the commit.
- <b>git log</b> - Used to see a list of previous commits

<i>note that the below commands are only relevant if using Github - other git clients will use different commands</i>

- <b>git remote</b> - Used to see the remote repo linked to the current git repo. If used with --v, you can see the Verbose version of the current location. You can also use this to add a github remote location.
- <b>git push</b> - Used to push commits up to the remote repo
- <b>git pull</b> - Used to pull the changes to a remote repo down to the local device.

Go to <[Github](https://github.com/new)> to create a new Repo. Github will walk you through the process.

## Bash
Bash is short for the "Bourne again shell", and is used to control a UNIX-based OS through a Command Line Interface. As with Git, there are a number of commands that allow for a range of functionality.

- <b>PWD</b> - Used to display the current location in the file tree
- <b>CD</b> - Used to change directory location. This can be with an absolute or relative path.
- <b>LS</b> - Used to list the contents of the current directory
- <b>MKDIR</b> - Used to create a new directory
- <b>TOUCH</b> - Used to make a new file. Any file extension can be specified.
- <b>ECHO</b> - Used to output text in the console.
- <b>CAT</b> - Used to print text from a file, or to combine multiple files. (Short for Concatenate)
- <b>OPEN</b> - Used to open a program from the current directory
- <b>CLEAR</b> - Used to clear the console
- <b>MV</b> - Used to change the location of a file or directory. This can also be used to change the name of a file/directory by "moving" it to an non-extant directory.

It's also worth noting that the ~ symbol is used to represent the home directory, and / is used to represent the root directory. For example, <i>CD ~</i> will send the user to the home directory.
