# linux-fundamentals
## Installation and Initial Setup
I created and AWS acount and signed in to the account
![aws console](./img/1.jpg)

Then I opened the instances console and created a new EC2 instance
![ec2](./img/2.jpg)

## Connecting to the Server
Downloaded key-pair to my downloads folder on my system, opened the system terminal and then connect to the server using SSH with the public address of the instance
![ssh](./img/3.jpg)

## Installing, Updating and Removing Software
I run the following command `sudo apt update` first to update the server
![update](./img/4.jpg)

Then I run `sudo apt install tree` to install tree
![tree](./img/5.jpg)

To confirm tree is intalled I run `tree /home`
![tree](./img/6.jpg)

And to remove tree I run `sudo apt remove tree`
![remove](./img/7.jpg)