Highly used Linux commands
## User-space Commands

### 1. echo
Usage: Print to screen

In: `echo Hi`
Out: `Hi`
### 2. ls
Usage: List files & directories on that location

In: `ls`
Out: `file.txt folder_name movie.mp4`

### 3. cd
Usage: Change Directory

In: `cd /patch/to/directory`
Out: `No output on screen`

### 4. pwd
Usage: Shows current working directory

In: `pwd`
Out: `/path/of/current/directory`

### 5. mkdir
Usage: Create directory or file to the specified path

In: `mkdir /path/to/create/newfolder`
Out: `No output on screen`

**Other Usages:-**
1. To create the complete path that doesn't exist. Use the `-p` flag.
		Example: `mkdir -p /path/that/need/to/create`
		
### 6. rm
Usage: To delete or remove a file

In: `rm filename.txt`
Out: `No output on screen`

**Other Usages:-**
1. To delete or remove a folder. Use the `-r` flag.
		Example: `rm -r /path/of/folder/to/delete`

### 7. cp
Usage: To copy a file

In: `cp /path/of/soucefile.txt /path/to/paste`
Out: `No output on screen`

**Other Usages:-**
1. To copy a folder. Use the `-r` flag.
		Example: `cp -r /path/of/folder/to/copy /path/to/paste`

### 8. touch
Usage: To create a new file with no contents

In: `touch new_file.txt`
Out: `No output on screen`

### 9. cat
Usage: To print file contents on screen

In: `cat file.txt`
Out: `Hi`

**Other Usages:-**
1. To add contents to a existing file. Use the `>` flag.
		Example: `cat > file.txt`
### Tips
1. To execute multiple commands in a single command, use `;` at the end of each command.
		Example: `cd new_dir; mkdir foldername; pwd`


