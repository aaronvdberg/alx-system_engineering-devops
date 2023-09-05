# Project 0x02. Shell, I/O Redirections and filters
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

Shell, I/O Redirection
What do the commands head, tail, find, wc, sort, uniq, grep, tr do
How to redirect standard output to a file
How to get standard input from a file instead of the keyboard
How to send the output from one program to the input of another program
How to combine commands and filters with redirections
Special Characters
What are special characters
Understand what do the white spaces, single quotes, double quotes, backslash, comment, pipe, command separator, tilde and how and when to use them
Other Man Pages
How to display a line of text
How to concatenate files and print on the standard output
How to reverse a string
How to remove sections from each line of files
What is the /etc/passwd file and what is its format
What is the /etc/shadow file and what is its format
Copyright - Plagiarism
You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
You are not allowed to publish any content of this project.
Any form of plagiarism is strictly forbidden and will result in removal from the program.
Requirements
General
Allowed editors: vi, vim, emacs
All your scripts will be tested on Ubuntu 20.04 LTS
All your scripts should be exactly two lines long ($ wc -l file should print 2)
All your files should end with a new line (why?)
The first line of all your files should be exactly #!/bin/bash
A README.md file, at the root of the folder of the project, describing what each script is doing
You are not allowed to use backticks, &&, || or ;
All your files must be executable
You are not allowed to use sed or awk
More Info
Read your /etc/passwd and /etc/shadow files.

Note: You do not have to learn about fmt, pr, du, gzip, tar, lpr, sed and awk yet.

## Technologies
- Script written in bash
- Tested on Ubuntu 20.4
- 
## Files
These files represent the different script files of the project and the description shows what the script does.
| FILES | DESCRIPTION |
| ----------- | ----------- |
| [`0-iam_betty`] | switches the current user to the user betty. The script should be a maximum of 8 characters and we assume the user *betty* exists. |
| [`1-who_am_i`] | Prints the effective username of the current user. |
| [`2-groups`]| Prints all the groups the current user is part of. |
| [`3-new_owner`] | Changes the owner of the file *hello* to the user **betty** |
| [`4-empty`]| Creates an empty file called *hello* |
| [`5-execute`] | Add execute permission to the owner of the file *hello* which is in the current directory |
| [`6-multiple_permissions`] | adds execute permission to the owner and the group owner, and read permission to other users, to the file *hello* in the working directory |
| [`7-everybody`] | Add execution permission to the owner, the group owner, and the other users, to the file *hello* which is in the working directory without using a comma in the script |
| [`8-James_Bond`] | sets the permission to the file *hello* as follows:  - Owner: No permission at all - Group: no permission at all - Other users: all the permissions |
| [`9-John_Doe`] | Set the mode of the file  *hello* which is in the working directory to this `- rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello`  without using a comma in the script |
| [`10-mirror_permissions`] | Sets the mode of the file *hello* the same as *olleh’s* mode. Both files  are in the working directory. |
| [`11-directories_permissions`] | Add execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users without changing regular files |
| [`12-directory_permissions`] | Creates a directory called *my_dir* with permissions 751 in the working directory. |
| [`13-change_group`]| changes the group owner to school for the file *hello* which is in the working directory |
| [`100-change_owner_and_group`] | Change the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory. |
| [`101-symbolic_link_permissions`] | Change the owner and the group owner of the symbolic link *_hello* in the working directory to `vincent` and `staff` respectively. |
| [`102-if_only`] | Change the owner of the file *hello* to `betty` only if it is owned by the user `guillaume`. the file is in the current directory.|
| [`103-Star_Wars`] | Play the StarWars IV episode in the terminal. |
