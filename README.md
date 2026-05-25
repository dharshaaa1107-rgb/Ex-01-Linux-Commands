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



<img width="762" height="60" alt="image" src="https://github.com/user-attachments/assets/6ad2fc69-7787-440e-b3b3-831822a20e24" />

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd


<img width="224" height="59" alt="image" src="https://github.com/user-attachments/assets/ec6b0f8a-eec7-45fa-8b2e-5bca840fb1d1" />

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>




<img width="851" height="106" alt="image" src="https://github.com/user-attachments/assets/fc53f6a5-09b3-403d-8b04-5bde5c62e78c" />

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>



<img width="795" height="112" alt="image" src="https://github.com/user-attachments/assets/ab5385b0-8baf-4cf4-b353-3bbd51d2bebb" />


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>




<img width="319" height="140" alt="image" src="https://github.com/user-attachments/assets/a3c4bc5e-fa8c-44ff-84e2-a0c818f14c5f" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..


 
 
 
 <img width="307" height="159" alt="image" src="https://github.com/user-attachments/assets/6d2c6a66-44d4-4d63-a276-d98d829d5c5a" />

### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>





<img width="302" height="122" alt="image" src="https://github.com/user-attachments/assets/25881378-a04d-40e5-9071-9c1080cc0647" />

### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name





<img width="447" height="34" alt="image" src="https://github.com/user-attachments/assets/32922a37-7819-47c9-99ca-ca4d44225e43" />


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>





<img width="263" height="80" alt="image" src="https://github.com/user-attachments/assets/c969dd09-6f91-42e7-9db9-db1e331ef7db" />

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>





 <img width="325" height="237" alt="image" src="https://github.com/user-attachments/assets/1b0a3096-c7c8-4e24-8022-34cc8deaafb6" />

## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files






<img width="398" height="152" alt="image" src="https://github.com/user-attachments/assets/ffa59536-c1c6-41c6-8d80-54edd5a7ddf2" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.



Syntax: head <file name>





<img width="351" height="468" alt="image" src="https://github.com/user-attachments/assets/ee335ed8-1d0d-45fc-bbbc-da526b7812bd" />


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>






<img width="258" height="203" alt="image" src="https://github.com/user-attachments/assets/d20d74f4-def2-4bc3-aeaf-cb8ead5ffb05" />

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id





<img width="1889" height="87" alt="image" src="https://github.com/user-attachments/assets/27546530-ca79-44db-a6cf-18d78ea79a2c" />


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>







<img width="304" height="62" alt="image" src="https://github.com/user-attachments/assets/7516cb8b-8d6e-49b4-af5f-bc068168fcf0" />


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>








<img width="416" height="267" alt="image" src="https://github.com/user-attachments/assets/d0049202-83a1-479f-8ec2-7eabfa706287" />

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>





<img width="402" height="105" alt="image" src="https://github.com/user-attachments/assets/1e234337-1507-41fa-8d58-e4be652922f4" />

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c



<img width="326" height="141" alt="image" src="https://github.com/user-attachments/assets/3b4c815b-719e-4c42-b65b-931592c49329" />

 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name






<img width="421" height="119" alt="image" src="https://github.com/user-attachments/assets/f632170e-7328-40cb-b46f-ce83e7dea76d" />

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….




<img width="209" height="62" alt="image" src="https://github.com/user-attachments/assets/7951244c-4af6-4278-840c-024521ca1782" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]







<img width="768" height="91" alt="image" src="https://github.com/user-attachments/assets/c974d6b8-1399-41b3-81c5-c86ddb110d77" />

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder




<img width="441" height="107" alt="image" src="https://github.com/user-attachments/assets/21c3f6ea-4c0a-4edd-a3a3-d300d7a27f79" />

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>






<img width="543" height="92" alt="image" src="https://github.com/user-attachments/assets/650487c8-1686-49df-b965-7ff77ca2089a" />


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..











<img width="1129" height="178" alt="image" src="https://github.com/user-attachments/assets/fd2bdfc1-4d3e-47b7-a8a4-baf7d2395aad" />


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>






<img width="223" height="271" alt="image" src="https://github.com/user-attachments/assets/0ac93028-3c2c-4e50-945e-63631d7396f3" />

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal







<img width="260" height="180" alt="image" src="https://github.com/user-attachments/assets/59b677b5-dc66-4493-85b4-43a9f5c666f3" />

### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear









<img width="882" height="840" alt="image" src="https://github.com/user-attachments/assets/b363f23a-aa6b-4b56-a48c-de1353fc8142" />


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>







<img width="459" height="216" alt="image" src="https://github.com/user-attachments/assets/c577c8de-8706-4b2d-a74e-a7cb33fd1a0f" />

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df










<img width="922" height="291" alt="image" src="https://github.com/user-attachments/assets/716a9804-b7ae-414a-bba4-f674bd92a09e" />

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”




<img width="263" height="77" alt="image" src="https://github.com/user-attachments/assets/b22f0a0b-5063-48d2-9d90-28f5a0c6798c" />






<img width="315" height="70" alt="image" src="https://github.com/user-attachments/assets/140e9e4d-a4bd-4b62-a769-d8c4049e68b0" />
















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
