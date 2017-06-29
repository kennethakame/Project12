      Project 12


1- what is UID? Unique ID, it is a alpha/numeri identifier that identifies individual account in the system.
2- what is GID ? GID stands for Group ID. It is a alpha/numeric number that identifies a group in the system.
3- what command do you type to check the UID of an account? # id <user name> eg in my school centos, my uid is 500
4- what command do you type to check what group an account belongs to? # id <user>

5- what command would you type to check a user's account component?
6- the -g of useradd command is used to add a user to a primary group. what is the option used to add a user to a subgroup or suplementary group? #Useradd -G
7- how do you get help on a linux server? To get help we may simply type the command we want to use with the option -–h or –-help. This will display all the information concerning that command. 
8- from a server prompt, how can you connect remotely to another server if you dont have access to putty. We can use the secure shell (ssh) to remotely connect to a linux server where we don’t have putty. The most basic form of the command is # ssh remote_host.
This command assumes that your username on the remote system is the same as your username on your local system.
The remote_host in this example is the IP address or domain name that you are trying to connect to.
If your username is different on the remote system, you can specify it by using this syntax:
•	ssh remote_username@remote_host
Once you have connected to the server, you will probably be asked to verify your identity by providing a password.
To exit back into your local session, simply type # exit

9- create a file on your server called yourname, then use scp to copy it to my server 

( 96.245.84.63 , username= class3 password= school1 ) put it in /tmp
# scp yourname class3@96.245.84.63:/tmp

10- download the redhat iso image from site ftp://96.245.84.63/software (login: class3 , password= school1 the iso image is rwd-rhel64i386.iso)

11- Watch the video on redhat installation in your video folder and then install redhat in your virtualbox.

