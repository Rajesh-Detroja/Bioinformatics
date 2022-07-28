## ls

`ls` command used to list files and folders in the current directory.

```bash
# list files and folders in current directory
ls
```

produces:

```bash
bash  bash.txt
```

Here, `bash` is a folder and `bash.txt` is a text file.

<br></br>

## --help

`--help` option can be use to view more options of any linux command.

```bash
# view more options of `ls` command
ls --help
```

produces:

```
Usage: ls [OPTION]... [FILE]...
List information about the FILEs (the current directory by default).
Sort entries alphabetically if none of -cftuvSUX nor --sort is specified.

Mandatory arguments to long options are mandatory for short options too.
  -a, --all                  do not ignore entries starting with .
  -A, --almost-all           do not list implied . and ..
      --author               with -l, print the author of each file
  -b, --escape               print C-style escapes for nongraphic characters
      --block-size=SIZE      with -l, scale sizes by SIZE when printing them;
                               e.g., '--block-size=M'; see SIZE format below
  -B, --ignore-backups       do not list implied entries ending with ~
  -c                         with -lt: sort by, and show, ctime (time of last
                               modification of file status information);
                               with -l: show ctime and sort by name;
                               otherwise: sort by ctime, newest first
  -C                         list entries by columns
```


**<ins>Note:</ins>** In linux, hidden files and folders are always starting with `.`

<br></br>

## ls -a

`ls -a` command used to list hidden files and folders in the current directory.

```bash
# list hidden files and folders in the current directory
ls -a
```

produces:

```
.  ..  .bash_file.txt  .bash_folder  bash  bash.txt
```

Here, `.bash_folder` is a hidden folder and `.bash_file.txt` is a hidden text file.

<br></br>

## ls -l

`ls -l` command used to list files and folders in the current directory with detailed information.

```bash
# list files and folders in the current directory with detailed information
ls -l
```

produces:

```
total 4.0K
drwxrwxr-x 2 rajesh rajesh 4.0K Jan 13 16:30 bash
-rw-rw-r-- 1 rajesh rajesh    0 Jan 13 16:30 bash.txt
```

<br></br>

## ls -al

`ls -al` command used to list hidden files and folders in the current directory with detailed information.

```bash
# list hidden files and folders in the current directory with detailed information
ls -al
```

produces:

```
total 16K
drwxrwxr-x  4 rajesh rajesh 4.0K Jan 13 16:51 .
drwxrwxr-x 10 rajesh rajesh 4.0K Jan 13 16:30 ..
-rw-rw-r--  1 rajesh rajesh    0 Jan 13 16:51 .bash_file.txt
drwxrwxr-x  2 rajesh rajesh 4.0K Jan 13 16:51 .bash_folder
drwxrwxr-x  2 rajesh rajesh 4.0K Jan 13 16:30 bash
-rw-rw-r--  1 rajesh rajesh    0 Jan 13 16:30 bash.txt
```

<br></br>

## ll

`ll` command is alias command of `ls -al`

`ll` command used to list all the files and folders in the current directory with detailed information.

```bash
ll
```

produces:

```
total 16K
drwxrwxr-x  4 rajesh rajesh 4.0K Jan 13 16:51 ./
drwxrwxr-x 10 rajesh rajesh 4.0K Jan 13 16:30 ../
-rw-rw-r--  1 rajesh rajesh    0 Jan 13 16:51 .bash_file.txt
drwxrwxr-x  2 rajesh rajesh 4.0K Jan 13 16:51 .bash_folder/
drwxrwxr-x  2 rajesh rajesh 4.0K Jan 13 16:30 bash/
-rw-rw-r--  1 rajesh rajesh    0 Jan 13 16:30 bash.txt
```

<br></br>

## ls -alh

`ls -alh` command used to list all the files and folders in the current directory with detailed information with human-readable size.

```bash
ls -alh
```

produces:

```
drwxrwxr-x  2 rajesh rajesh 4.0K Jul  2 07:10 bash
-rw-rw-r--  1 rajesh rajesh    0 Jul  2 07:30 .bash_file.txt
drwxrwxr-x  2 rajesh rajesh 4.0K Jul  2 07:30 .bash_folder
-rw-rw-r--  1 rajesh rajesh    0 Jul  2 07:10 bash.txt
```

<br></br>

## ls -alht

`ls -alht` command used to list files and folders in the current directory and sort it by modification (created/edited) time.

```bash
ls -alht
```

produces:

```
-rw-rw-r--  1 rajesh rajesh    0 Jul  2 07:30 .bash_file.txt
drwxrwxr-x  2 rajesh rajesh 4.0K Jul  2 07:30 .bash_folder
-rw-rw-r--  1 rajesh rajesh    0 Jul  2 07:10 bash.txt
drwxrwxr-x  2 rajesh rajesh 4.0K Jul  2 07:10 bash
```

<br></br>

## cd

`cd` command used to change the directory.

```bash
# go to home directory from current directory
cd
```

**<ins>Note:</ins>** Use `TAB` to complete the name of the files and folders written after any linux command.

```bash
# go to `bash` directory using `cd` command
cd bash/
```

**<ins>Note:</ins>** Use double `TAB` to list files and folders of written directory after any linux command.

```bash
# go to given path directory using `cd` command
cd learnings/linux/bash/
```

```bash
# go to parent (directory that is 1 level back) directory
cd ..
```

```bash
# go to directory that is 2 level back
cd ../../
```

**<ins>Note:</ins>** Like that `..` can be used to go to as many parent directories.

<br></br>

## clear

`clear` command used to clear the current terminal screen.

<br></br>

## pwd

`pwd` command used to get the path (location) of the current directory.

**<ins>Note:</ins>** New terminal tab can be opened using `ctrl + shift + t` or Right click on the current terminal and the click on `New Tab`.
