# CMD-Challenge-Solutions

This repository is for the for all the solutions and read-ups for the command line challenge. Since the challenges are one liners so with the solutions the following info on the command will be updated.  

Link to the challenge: https://cmdchallenge.com/

## Challenges and Solutions

### Question 1 - Print "hello world".

Command: [echo](http://linuxcommand.org/lc3_man_pages/echoh.html) 

Description: Echo the STRING(s) to standard output.

```
echo "hello world" 
```

### Question 2 - Print the current working directory.

Command: [pwd](https://linux.die.net/man/1/pwd)

Description: Print the full filename of the current working directory.

```
pwd
```

### Question 3 - List names of all the files in the current directory.

Command: [ls](https://linux.die.net/man/1/ls)

Description: List information about the FILEs (the current directory by default)

```
ls 
```

### Question 4 - There is a file named "access.log" in the current directory. Print the contents.

Command: [cat](https://linux.die.net/man/1/cat) 

Description: Concatenate FILE(s), or standard input, to standard output.

```
cat
```

### Question 5 -  Print the last 5 lines of "access.log".

Command: [tail](https://linux.die.net/man/1/tail)

Description: Print the last 10 lines of each FILE to standard output. With more than one FILE, precede each with a header giving the file name. With no FILE, or when FILE is -, read standard input.

```
tail -5 access.log
```

### Question 6 -  Create an empty file named take-the-command-challenge in the current working directory.

Command: [touch](https://linux.die.net/man/1/touch)

Description: Update the access and modification times of each FILE to the current time. A FILE argument that does not exist is created empty, unless -c or -h is supplied. A FILE argument string of - is handled specially and causes touch to change the times of the file associated with standard output

```
touch take-the-command-challenge
```

### Question 7
Create a directory named tmp/files in the current working directory

Hint: The directory "tmp/" doesn't exist, with one command you need to create both "tmp/" and "tmp/files"

Description:

Command: [mkdir](https://linux.die.net/man/1/mkdir)

```
mkdir -p tmp/files
```

### Question 8
Copy the file named take-the-command-challenge to the directory tmp/files

 Description: Copy SOURCE to DEST, or multiple SOURCE(s) to DIRECTORY.
 
 Command: [touch](https://linux.die.net/man/1/cp)

```
cp take-the-command-challenge tmp/files
```


### Question 9
Move the file named take-the-command-challenge to the directory tmp/files

Description:

Command:  

```
mv take-the-command-challenge tmp/files
```



### Question 10
A symbolic link is a type of file that is a reference to another file.
Create a symbolic link named take-the-command-challenge that points to the file tmp/files/take-the-command-challenge.

Description:


Command:  

```
mv take-the-command-challenge tmp/files
```

### Question 11
Move the file named take-the-command-challenge to the directory tmp/files

Description:

Command:  

```
mv take-the-command-challenge tmp/files
```

### Question 12
Move the file named take-the-command-challenge to the directory tmp/files

Command:  

```
mv take-the-command-challenge tmp/files
```

### Question 13
Move the file named take-the-command-challenge to the directory tmp/files

Command:  

```
mv take-the-command-challenge tmp/files
```

### Question 14
Move the file named take-the-command-challenge to the directory tmp/files

Command:  

```
mv take-the-command-challenge tmp/files
```

### Question 15
Move the file named take-the-command-challenge to the directory tmp/files

Command:  

```
mv take-the-command-challenge tmp/files
```


### Question 16
Move the file named take-the-command-challenge to the directory tmp/files

Command:  

```
mv take-the-command-challenge tmp/files
```

### Question 17
Move the file named take-the-command-challenge to the directory tmp/files

Command:  

```
mv take-the-command-challenge tmp/files
```

### Question 18
Move the file named take-the-command-challenge to the directory tmp/files

Command:  

```
mv take-the-command-challenge tmp/files
```

### Question 19
Move the file named take-the-command-challenge to the directory tmp/files

Command:  

```
mv take-the-command-challenge tmp/files
```

### Question 20
Move the file named take-the-command-challenge to the directory tmp/files

Command:  

```
mv take-the-command-challenge tmp/files
```

### Question 22
Move the file named take-the-command-challenge to the directory tmp/files

Command:  

```
mv take-the-command-challenge tmp/files
```

### Question 23
Move the file named take-the-command-challenge to the directory tmp/files

Command:  

```
mv take-the-command-challenge tmp/files
```

### Question 24
Move the file named take-the-command-challenge to the directory tmp/files

Command:  

```
mv take-the-command-challenge tmp/files
```

### Question 25
Move the file named take-the-command-challenge to the directory tmp/files

Command:  

```
mv take-the-command-challenge tmp/files
```

### Question 26
Move the file named take-the-command-challenge to the directory tmp/files

Command:  

```
mv take-the-command-challenge tmp/files
```

### Question 27
Move the file named take-the-command-challenge to the directory tmp/files

Command:  

```
mv take-the-command-challenge tmp/files
```

### Question 28
Move the file named take-the-command-challenge to the directory tmp/files

Command:  

```
mv take-the-command-challenge tmp/files
```

### Question 29
Move the file named take-the-command-challenge to the directory tmp/files

Command:  

```
mv take-the-command-challenge tmp/files
```

### Question 30
Move the file named take-the-command-challenge to the directory tmp/files

Command:  

```
mv take-the-command-challenge tmp/files
```












### Question none - There is a file named "access.log" in the current working directory. Print all lines in this file that contains the string "GET".

Command: [grep](https://linux.die.net/man/1/grep)

Description: grep searches the named input FILEs (or standard input if no files are named, or if a single hyphen-minus (-) is given as file name) for lines containing a match to the given PATTERN. By default, grep prints the matching lines.

```
grep "GET" access.log
```

### Question none - Print all files in the current directory,one per line (not the path, just the filename) that contain the string "500".

Command: 

Description:

```
grep -l 500 *

```

## Author
Sunday JIMOH
