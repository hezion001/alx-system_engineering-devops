# 0x03. Shell, init files, variables and expansions
## Requirements
### General
- Allowed editors: vi, vim, emacs
- All your scripts will be tested on Ubuntu 20.04 LTS
- All your scripts should be exactly two lines long ($ wc -l file should print 2)
- All your files should end with a new line (why?)
- The first line of all your files should be exactly #!/bin/bash
- A README.md file, at the root of the folder of the project, describing what each script is doing
- You are not allowed to use &&, || or ;
- You are not allowed to use bc, sed or awk
- All your files must be executable
## Tasks
### 0. <o>
Create a script that creates an alias.
- Name: ls
- Value: rm *
### 1. Hello you
Create a script that prints hello user, where user is the current Linux user.
### 2. The path to success is to take massive, determined action
Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
