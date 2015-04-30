# bash-information

A small script that returns information about the current Kernel and system.

#### 
    $ ./information -[option]

### -k

Prints basic information about the kernel

#### 
    $ ./information -k

### -p

Prints the number of processes for the currently logged in user
#### 
    $ ./information -p

### -u

Prints information about users in /etc/passwd
#### 
    $ ./information -u


### -g

Prints a list of users, and all groups belonging to that user
#### 
    $ ./information -g


### -l

Prints a list of top 10 largest files location in the users home folder
#### 
    $ ./information -l


### -d

Counts all files in a specified directory
#### 
    $ ./information -d


### -v

Using SHELL variables, prints username, home, shell and path
#### 
    $ ./information -v


### -a

Run all functions
#### 
    $ ./information -a
