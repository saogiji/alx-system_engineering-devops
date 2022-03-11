# 0x0A. Configuration management
## Introduction
Configuration management (CM) refers to the process of systematically handling changes to a system in a way that it maintains integrity over time. Even though this process was not originated in the IT industry, the term is broadly used to refer to server configuration management.
It is common to refer to configuration management tools as Automation Tools or IT Automation Tools.
Another common term used to describe the automation features implemented by configuration management tools is Server Orchestration or IT Orchestration, since these tools are typically capable of managing one to hundreds of servers from a central controller machine.
There are a number of configuration management tools available in the market. Puppet, Ansible, Chef and Salt are popular choices. Although each tool will have its own characteristics and work in slightly different ways, they are all driven by the same purpose: to make sure the system’s state matches the state described by your provisioning scripts.
## Projects/tasks
This directoy contains task done for the ALX Software Engineering Program, some of the tasks carried out inludes;
### 0. Create a file
Using Puppet, create a file in /tmp.

Requirements:

File path is /tmp/school
File permission is 0744
File owner is www-data
File group is www-data
File contains I love Puppet
### 1. Install a package
Using Puppet, install puppet-lint.

Requirements:

Install puppet-lint
Version must be 2.5.0

### 2. Execute a command
Using Puppet, create a manifest that kills a process named killmenow.

Requirements:

Must use the exec Puppet resource
Must use pkill