# 0x0C. Web server
## Introduction
Computers connected to the web are called clients and servers.
* Clients are the typical web user's internet-connected devices (for example, your computer connected to your Wi-Fi, or your phone connected to your mobile network) and web-accessing software available on those devices (usually a web browser like Firefox or Chrome).
* Servers are computers that store webpages, sites, or apps. When a client device wants to access a webpage, a copy of the webpage is downloaded from the server onto the client machine to be displayed in the user's web browser.
In addition to the client and server discussed above, other requirements of a web server includes;
* Internet connection
* TCP/IP
* DNS
* HTTP
* Component files such as code files and assets.

## Projects/Tasks
This directory contains projects carried out by saogiji for the ALX Software Engineering Program, some of the tasks includes;

### 0. Transfer a file to your server
A Bash script that transfers a file from a client to a server:
Requirements:
* Accepts 4 parameters
	1. The path to the file to be transferred
	2. The IP of the server we want to transfer the file to
	3. The username scp connects with
	4. The path to the SSH private key that scp uses
* Display Usage: 0-transfer_file PATH_TO_FILE IP USERNAME PATH_TO_SSH_KEY if less than 3 parameters passed
* scp must transfer the file to the user home directory ~/
* Strict host key checking must be disabled when using scp

### Install nginx web server
Installing a web server nginx
Requirements:
* Install nginx on a web server web-01
* server
* Nginx should be listening on port 80
* When querying Nginx at its root / with a GET request (requesting a page) using curl, it must return a page that contains the string Hello World!
* As an answer file, write a Bash script that configures a new Ubuntu machine to respect above requirements (this script will be run on the server itself)
* You can’t use systemctl for restarting nginx