# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls
 <img width="762" height="60" alt="image" src="https://github.com/user-attachments/assets/d6971757-1d5a-40d7-bbd0-e27e952a29f5" />



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
<img width="224" height="59" alt="image" src="https://github.com/user-attachments/assets/746b7fd6-1196-47a6-b7be-990f52850836" />

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
<img width="851" height="106" alt="image" src="https://github.com/user-attachments/assets/cb329885-fe11-4673-a45e-7101f7b258c7" />


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
<img width="795" height="112" alt="image" src="https://github.com/user-attachments/assets/b0ca63af-d972-4197-9982-a3e2f3adc633" />


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
<img width="319" height="140" alt="image" src="https://github.com/user-attachments/assets/750b4bb7-0f9c-49c9-8de7-fa32343edfe6" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
<img width="307" height="159" alt="image" src="https://github.com/user-attachments/assets/3f703948-ed37-4cd7-b740-429ecc5a1b3d" />

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="302" height="122" alt="image" src="https://github.com/user-attachments/assets/1baf8330-ec9e-4155-80b5-0d994f243c9a" />


### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
<img width="447" height="34" alt="image" src="https://github.com/user-attachments/assets/de4d874b-305f-43a6-a41f-518a8b4ae235" />



### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="263" height="80" alt="image" src="https://github.com/user-attachments/assets/ffe96afd-c08b-47be-9bb0-8c24f31d6426" />


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

<img width="325" height="237" alt="image" src="https://github.com/user-attachments/assets/b82ec7c7-b9b8-42d6-95c1-fa408885f829" />

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="398" height="152" alt="image" src="https://github.com/user-attachments/assets/a48b6577-956a-4704-84b3-3e78bfe38be7" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="351" height="468" alt="image" src="https://github.com/user-attachments/assets/a21056d1-6bbd-4919-b5a1-9dac7a6f4f10" />


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

<img width="258" height="203" alt="image" src="https://github.com/user-attachments/assets/3c8524e0-5cc6-4ca8-b6b8-dbf55dcf2a01" />

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
<img width="1889" height="87" alt="image" src="https://github.com/user-attachments/assets/e80746d3-2071-4edb-a295-153a144e87ca" />



### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="304" height="62" alt="image" src="https://github.com/user-attachments/assets/12698a73-f6b2-4af7-9a18-667e2636fcf6" />


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
<img width="416" height="267" alt="image" src="https://github.com/user-attachments/assets/894404c0-6c59-48d4-9401-f585b5677313" />


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>
<img width="402" height="105" alt="image" src="https://github.com/user-attachments/assets/028804d9-74e2-4394-ac76-6a36ac926509" />


### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
<img width="326" height="141" alt="image" src="https://github.com/user-attachments/assets/5c62aa39-c4a3-4b8a-9868-d6862b851348" />

 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name



### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
