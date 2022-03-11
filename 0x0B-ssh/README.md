# 0x0B. SSH
## Introduction
A server is a piece of computer hardware or software (computer program) that provides functionality for other programs or devices, called "clients".
Servers can provide various functionalities, often called "services", such as sharing data or resources among multiple clients, or performing computation for a client.
A single server can serve multiple clients, and a single client can use multiple servers.
A client process may run on the same device or may connect over a network to a server on a different device.
Typical servers are database servers, file servers, mail servers, print servers, web servers, game servers, and application servers.
## Projects/Task
This directory contains tasks carried out for the ALX Software Engineering Program, some of the tasks carried out includes;
### 0. Use a private key
Write a Bash script that uses ssh to connect to your server using the private key ~/.ssh/school with the user ubuntu.
Requirements:
* Only use ssh single-character flags
* You cannot use -l
* You do not need to handle the case of a private key protected by a passphrase  

### 1. Create an SSH key pair
Write a Bash script that creates an RSA key pair.

Requirements:

* Name of the created private key must be school
* Number of bits in the created key to be created 4096
* The created key must be protected by the passphrase betty

### 2. Client configuration file2. 
Requirements:

*Configuring  SSH client to use the private key ~/.ssh/school
* Configuring SSH client to refuse to authenticate using a password

