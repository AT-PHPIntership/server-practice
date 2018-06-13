
# The `|` symbol 
The result in the left is the param for the right

```bash
$ history | grep cd
$ cat backup.sql | mysql -u root -p test mydb 
```

# System

### Listing proccess
```bash
$ ps
```

## Help
Show command manual
```bash
$ man
```

```
# man cd
```

# FILE AND DIRECTORY

## Listing file and directory
```bash
$ ls <option> <directory>
```
- `-l` listing with peropety: owner, permission, time, size ...
- `-a` include hidden file and hidden directory

```bash
$ ll 
# same ls -l
```
```bash
$ ll -a
# same ls -al
```

## Get current directory
```bash
$ pwd
```

## Go to directory
```bash
$ cd <directory>
```

## Show file content
```bash
$ cat <filename>
```

## copy file
```bash
$ cp
```

## Move file or rename file
```bash
$ mv 
```

## Make directory
```bash
$ mkdir
```

## Remove file
```bash
$ rm 
# sudo rm -rf /*
```

## Create file
```bash
$ touch filename
```

## Show the tail file
```bash
$ tail
$ tail -f #show and keep the output, it is useful to check file change realtime
$ tail -n 10 # show the last 10 lines
```

## Open file in nano editor
```bash
$ nano test.txt
```

## Open file in Vim editor
```bash
$ vim index.php
```


# OWER, PERMISSION

## Login to root user
```bash
$ sudo su
```

## Set file permission

```bash
$ chmod <option> <specification> file
# chmod -R 777 storage
# chmod 644 index.php
```

## Set owner for file
```bash
$ chown <option> <user>:<group> file
```

# Search

## Search file or directory
```bash
$ find
```

## Find string in file
```bash
$ grep
# grep display_errors /etc/php.ini
```

# Network

## Show network information
```bash
$ ifconfig
```

## Show information and statistics about protocols 
```bash
netstat
```