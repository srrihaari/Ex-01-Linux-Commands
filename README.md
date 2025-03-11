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
![421250329-ab422181-719e-4b65-b059-d2a84c6f2f8f](https://github.com/user-attachments/assets/7e34042b-ef8b-435d-badd-e77c71a90a11)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![421250393-6cd07e44-1b18-4ba5-90e7-4e6ee76419ac](https://github.com/user-attachments/assets/7a2c6343-4d34-477e-8898-63947fe5612b)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir
![421250441-fef8b509-03b0-4856-a57a-65b137cc9f9d](https://github.com/user-attachments/assets/8229350c-8c6a-4d76-b462-9bb1f648a58b)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir
![421250691-59f23650-63a7-4f44-8ac8-7af62c2cdb4d](https://github.com/user-attachments/assets/c24b8310-4725-463c-aefc-0bb71591ab2a)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd

![421250690-298b5c15-fc7f-438e-8048-abfcaefc9fec](https://github.com/user-attachments/assets/9f8a0dd6-4211-44e1-acfa-ed143ae2a811)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
![421250692-bfe97b21-e1e3-4bd9-a47d-580aab3a7184](https://github.com/user-attachments/assets/0a0bde8f-fac4-40e2-89c6-68288aaf1f7a)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp 
![421250694-6a33293c-7e81-484e-83dd-08af68413870](https://github.com/user-attachments/assets/647c0371-613d-4295-96eb-cde2c1697206)



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
![421250695-7003e715-db57-464e-9699-423074cf271c](https://github.com/user-attachments/assets/22c9ab4d-b936-45d6-ac26-2add1d01f927)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
![421250721-e1ab4949-44c8-4952-bece-8aa0b4c3f40d](https://github.com/user-attachments/assets/e8afae96-1d5a-4fea-945d-3cf60c512c14)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv 

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
![421250934-61fec5a5-c99f-45ee-a7f7-e5fb261e2583](https://github.com/user-attachments/assets/a7370491-8e46-4024-8765-192649ae8756)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head 
![421250972-b3d3704f-fcbd-47ae-8a7b-e2ce933f932d](https://github.com/user-attachments/assets/a504aa8a-c34f-4ccb-be4d-3f1e07737412)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail 

![421251249-3ff9e86b-551a-4a7a-b52e-7194190b9e86](https://github.com/user-attachments/assets/cfda18b7-5165-4e34-8928-2886507b1a22)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
![421251382-a9b2afb5-9ce2-4878-85e1-dac74c80f5d7](https://github.com/user-attachments/assets/6117499d-7249-48af-a6d1-07e0f500770c)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep 
![421251434-b292513b-8c1e-4e46-b23c-719096843296](https://github.com/user-attachments/assets/7b46d3f6-2597-46bb-b9f6-0d52c0b0ba6e)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
![421251434-b292513b-8c1e-4e46-b23c-719096843296](https://github.com/user-attachments/assets/c268ebf0-fbbc-4b98-9a12-a1d25dec9aa4)

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name
![421251843-410f9355-48d1-4b79-a1ab-2ded3650d4da](https://github.com/user-attachments/assets/92207628-292f-4867-9e6a-0fdba048e1cc)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
![421252012-90749fa9-ab08-4a23-9a67-fc976cf8fb42](https://github.com/user-attachments/assets/3f8d5bc4-1714-4793-acbf-a9c8d0d51912)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
![421252063-24b0e0e5-7b0c-4881-a92e-2c787d5dbce3](https://github.com/user-attachments/assets/22f69b69-291a-4652-a2ee-8c87dcc7a811)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host or
![421252171-e8da20fe-e347-40b4-a025-e9d53b3bc0fe](https://github.com/user-attachments/assets/11dda7ed-5873-481d-a222-c11d30148158)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip 
![421252229-62a8ee1a-8466-4458-b0a4-dd823696b9c3](https://github.com/user-attachments/assets/2f229bb5-103c-458f-9194-d92894df753c)

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort 

![421252307-0de974e1-01b8-4df6-a916-bce6aba7d36c](https://github.com/user-attachments/assets/bbf18693-45f2-4011-aa4a-b6eb4bfc175c)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
![421252378-7e44c971-f094-42b3-9d70-ce39cb540413](https://github.com/user-attachments/assets/adea2cd3-73c6-45fe-81cb-e77df458d14c)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
![421252413-aeb16faf-4aa8-4988-b7a2-b1f1d9b933fa](https://github.com/user-attachments/assets/0c64d8f1-ffd8-4b52-a76c-eab8f494dbc3)



### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" 
![421252448-939fd86f-50a7-45a7-9cf9-025c58c7e86c](https://github.com/user-attachments/assets/0dd1f6d9-7168-4e42-a729-1b089aa7a342)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![421252477-11c02ecd-9aca-498c-be46-76229dd8d2d2](https://github.com/user-attachments/assets/fb9548d8-ab4e-47cc-9fb9-7236f520f67d)




### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.

