# WindowServerCalpolyStudents
a tutorial on how to use a ec2 server for your windows needs.

This tutorial is meant for Unix operating systems meaning macOS, linux, BSD ect.. In this tutorial im using arch linux so it might be differnt for your guys but the same concepts apply.

## Parts
1.) create an ec2 windows instance

2.) install a RPD application

3.) log into the EC2 instance using the application installed in Part 2

### Part 1
Use this tutorial to help create an intsance of the ec2 windows server: https://www.youtube.com/watch?v=5FepK5pV39c, make sure you download the .pem file - for the password.

After creating the instance - go to instances on the left side panel of and right click on the instance you just created. Click on get Windows password, it will next have an option to upload a .pem file in order to decryct it an get your password. Next your password will show copy it and save it for later.

While being in the Instance tab still also record:

1.)Public DNS (IPv4)

2.)Pv4 Public IP



### Part 2
For linux user I would recommend installing remmina which is an application to install. Follow the instruction here: (https://remmina.org/how-to-install-remmina/

For Mac users I didnt try using this application coRD but it should work. Follow the instructions here on how to install: http://cord.sourceforge.net/

### Part 3

Open up the application installed in part 2 it should look something like this:

![image remmina](https://github.com/ByVictorrr/WindowServerCalpolyStudents/blob/master/ink%20.png)

click the + button:

![image remmina add ](https://github.com/ByVictorrr/WindowServerCalpolyStudents/blob/master/ink%20(1).png)

click on protocol and select RPD

Enter in Server field: Pv4 Public IP

Enter in  Username: Administrator

Enter in User Password: ******** (Found in part 1)

Enter in Domain: Public DNS (IPv4)


Finally press save and connect, it should look something like this.


![log in](https://github.com/ByVictorrr/WindowServerCalpolyStudents/blob/master/ink%20(1).png)

#### Final Notes

I recommend downloading https://gitforwindows.org/ on windows for easy pull and push on your main computer is your familar with git.


