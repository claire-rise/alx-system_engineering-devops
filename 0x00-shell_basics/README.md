## This is the readme for sudirectory 0x00-shell_basics

### Task 0: Where am I?

Write a script that prints the absolute path name of the current working directory.

### Output
#### /root/alx-system_engineering-devops/0x00-shell_basics

### Repo:
- GitHub repository: alx-system_engineering-devops
- Directory: 0x00-shell_basics
- File: 0-current_working_directory

### Task 1: What’s in there?

Display the contents list of your current directory.

### Output: Dummy
#### Applications    Documents   Dropbox Movies Pictures
#### Desktop Downloads   Library Music Public

### Repo:
- GitHub repository: alx-system_engineering-devops
- Directory: 0x00-shell_basics
- File: 1-listit

### Task 2: There is no place like home

Write a script that changes the working directory to the user’s home directory.

- You are not allowed to use any shell variables

### Output: Example
#### julien@ubuntu:/tmp$ pwd
#### /tmp
#### julien@ubuntu:/tmp$ echo $HOME
#### /home/julien
#### julien@ubuntu:/tmp$ source ./2-bring_me_home
#### julien@ubuntu:~$ pwd
#### /home/julien
#### julien@ubuntu:~$

### Repo:
- GitHub repository: alx-system_engineering-devops
- Directory: 0x00-shell_basics
- File: 2-bring_me_home

### Task 3: The long format

Display current directory contents in a long format

### Output: Example
#### $ ./3-listfiles
#### total 32
#### -rwxr-xr-x@ 1 sylvain staff 18 Jan 25 00:19 0-current_working_directory
#### -rwxr-xr-x@ 1 sylvain staff 19 Jan 25 00:23 1-listit
#### -rwxr-xr-x@ 1 sylvain staff 18 Jan 25 00:29 2-bring_me_home
#### -rwxr-xr-x@ 1 sylvain staff 18 Jan 25 00:39 3-listfiles
#### $

### Repo:
- GitHub repository: alx-system_engineering-devops
- Directory: 0x00-shell_basics
- File: 3-listfiles
