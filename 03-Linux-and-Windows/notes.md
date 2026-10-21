# Linux and Windows

> Study notes transcribed from my personal learning document. These are works in progress, not verified technical guidance.

## Windows

Cd: same  use as the linux  
Dir/ dir /a: shows all files within that directory/ shows all hidden files  
Dir /s: can be used to find a file using Dir /s….  
Type: reads the thing  
Example of full path  
Systeminfo: shows the info of the system  
Ipconfig  
When trying to log into someone’s account from afar using linux  
Use the command, ssh Username Ip address  
Don’t worry if u can’t see what you’re typing that’s normal  

## Linux fundementals

Echo: same as print in python  
Whoami: list user  
Pro tip: When using the terminal, you can press the up and down arrow keys on your keyboard to scroll through commands that you have already entered.  
Keys: …. Means add the name of what you are searching for  
Commands basics  
File System Navigation: Learn how to move between folders (cd)- cd<filename> example: cd Documents. To go back one level (cd ..) . check your current location (pwd), and list files (ls -a).  
Find: can be used to find files and where they are hidden, find ~ -name……  
Help Mechanisms: Master finding information on the fly using the man command (manual pages) or appending --help to any command.  
Permissions & Privileges: Understand how administrative access works using sudo and how to read file permissions (chmod).  
Pipelines & Filtering: Learn how to send the output of one command into another using the pipe (|) operator and how to search text using grep.  
Standard Input/Output: Understand how to read files (cat ….or less) and redirect outputs to new files (> or >>).  
Df -h: shows all the space currently in use or not used  
: is the same as assigning a variable such as echo Tryhackme > thm  
However, echo must be said before for it to be output  
Cat then reads it  
Ssh: used to login into someone else’s account or email as long as you know their ip address  
More commands  
Always add the name of what you want after it.  
However cp requires the name of the file you are copying and then the name of the file you are moving the copy to  
File:shows what file it is  
Su: switch between users  
Nano: a command that has to be followed by a file name to create that file or edit an existing one  
Control y to save and execute it  
Wget: used to download files however 2 separate terminals have to be active  
Scp: used to copy files safely can be used to transfer the files through users using ssh  
Kill: used to legit kill a process happening in the background however you have to state which PID you wanna kill  
Systemctl:  this command allows us to interact with the systemd process/daemon. Continuing on with our example, systemctl is an easy to use command that takes the following formatting: systemctl [option] [service]  
Fg: used to bring processes to the foreground  
Crontab: used to choose what time or what u need during a booting (crontab generator)  

## Windows fundamental

Msconfig: is a command you type into win + r to show all the configs that are ready when an os boots up  
View advanced settings allows for editing boot up sequences and such  
Then theres computer management, which works on tasks, events, storages and processes  
Another way to find an ip address is simply  
Windows + r > msconfig>tools>system info  
This method can be used  for so many things  
