**Core Components of Linux**
- **kernal**: Heart of the linux, It is written in C language and on top of this multiple distributions are built like ubuntu, CentOS, RHEL, SUSE etc. It also helps to convert user instruction into hardware language.
- **User Space**: All the Users created in linux having thier home directory created at location /home/user
- **init/systemd**: It's deamon process which is the 1st process running when liunx boot up, and monitor every single thing in the system.

**Explain Process States**
- **Running**: When we use any command its process is created and once it got resources it goes into running state
- **Sleeping**: When the process is dependent on the another process, or waiting for any resources to be free
- **Zombie**: when the parent process of the child process ends and not send the exit signal to child process then it beccomes zombie

**5 Daily used Commands**
- **CAT**: To display content of the file
- **CD**: To change the directory
- **PWD**: present working directory
- **LS**: list all the files and DIRs from the current directory
- **PS**: list all the process on server
