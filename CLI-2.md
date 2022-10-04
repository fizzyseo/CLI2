## CLI(Command LIne Interface)-2

### Standard Output
By default, standard output is screen.
You can redirect output using ">" aftera a command (ls) to create and save the output in a file
Using ">>" appends output to an extising file (if it already exitsts),
or create and write to a new file if it doesn't exist.

### Standard Input
By default, standard input is from keyboard.
You can redirect input from a file using "<"
You can mix "<" and ">" together in a single line

### Pipelines '|'
feeds output of previous command to input of next command

### Expansion
Special characters expand its meaning when given to shell commands
eg) *, ~

### Permissions   
Files and directories have a permission assigned differently to owner/ group/ others.
---   
File type : - indicates regular file
            d indicates directory
rwx : read, write, execute
---   
"chmod" changes permissions
eg. '6' of 600 = 110 = rw- for owner

### Superuser
A superuser has all system administation authority
Some commands need superuser's pribilleges
Put "sudo" before the command if you are a superuser
