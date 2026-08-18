Write a script that changes the working directory to the user’s home directory.

    You are not allowed to use any shell variables

julien@ubuntu:/tmp$ pwd
/tmp
julien@ubuntu:/tmp$ echo /root
/home/julien
julien@ubuntu:/tmp$ source ./0-bring_me_home
julien@ubuntu:~$ pwd
/home/julien
julien@ubuntu:~$
