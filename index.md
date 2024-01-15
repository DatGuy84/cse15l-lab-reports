# Lab Report 1 - Remote Access and FileSystem

## CD
![Image](https://github.com/DatGuy84/cse15l-lab-reports/assets/148490937/38488f72-f65b-4b23-b562-a76835d4dd5a)

```
In the first line where cd has no arguments, the directory was home. The command "cd" changes the directory to home,
and since the directory was already at home, there were no changes.  Therefore, there is no error when cd is typed out.
```
![Image](https://github.com/DatGuy84/cse15l-lab-reports/blob/main/CD%20Lecture1.png?raw=true)
```
This code was ran in the home directory.  Additionally, the directory was changed to lecture1 because the command cd
followed by the argument "lecture1/" causes the directory to be changed to lecture1.  There are no errors in this output.
```
![Image](https://github.com/DatGuy84/cse15l-lab-reports/blob/main/CD%20README.png?raw=true)
```
This code was ran in the lecture1 directory.  The output was an error because the cd tried to change the directory to a file.
The file is not considered a directory, so an error was created.
```

## ls

![Image](https://github.com/DatGuy84/cse15l-lab-reports/blob/main/ls%20no%20arguments.png?raw=true)

```
The working directory of this code was the home directory.  Because the file under home was lecture1, lecture1 was the
only output produced when the command ls was typed.  There is no error.
```

![Image](https://github.com/DatGuy84/cse15l-lab-reports/blob/main/ls%20lecture1.png?raw=true)

```
The working directory was the home directory. The command ls prints out all the files under the directory, so it printed
out all the files in lecture1 since the argument was lecture one.  There are no errors.
```

![Image](https://github.com/DatGuy84/cse15l-lab-reports/blob/main/ls%20README.png?raw=true)

```
The working directoy was the home directory.  Since the ls command's argument is a file, it just lists the pathway
from the working directory to the file.  This is not an error because using an ls command on a file allows people
to know the pathway from the folders to a certain file.
```

## cat
![Image](https://github.com/DatGuy84/cse15l-lab-reports/blob/main/Cat%20no%20arguments.png?raw=true)

```
The working directory was the home directory.  With the command cat, there is nothing being printed since there is no
file.  There is no error.
```

![Image](https://github.com/DatGuy84/cse15l-lab-reports/blob/main/cat%20Lecture1.png?raw=true)

```
The working directory was the home directory.  Since the cat command's argument is a folder, its contents cannot be
printed.  This is an error because the cat command is only meant to be used to print out the contents of a file
and not a folder.
```

![Image](https://github.com/DatGuy84/cse15l-lab-reports/blob/main/cat%20README.png?raw=true)

```
The working directory was the home directory.  Since the cat command's argument is a file, its contents can be
printed out.  There is no error.
```
