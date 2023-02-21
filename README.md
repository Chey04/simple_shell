<h1 align="center">
  0x16. C - Simple Shell
</h1>

<p align="center">
	:shell: 🐚 :ocean: 🌊
</p>

## Overview

This project is a realization of a basic command-line interface for UNIX, commonly known as a shell. It was developed as a pivotal project for the C programming language course at ALX Africa Software Engineering, aimed at enhancing participants' comprehension of sophisticated concepts related to shell programs, such as system calls, file manipulation, process control, and error handling. The shell is exclusively coded in the C programming language.


## COPYRIGHT

&copy; 2023 by [**Chinemerem Chukwukere**](https://github.com/Chey04) and [**Emeka Emodi**](https://github.com/emmy3000). All rights reserved.


## Description :

The Unix command interpreter, commonly known as the shell, is a program that provides users with a command-line interface for interacting with the operating system. The shell takes input from the user, interprets it, and executes the corresponding command. This implementation of the shell replicates the functionality of the simple shell (sh) found in Unix-like operating systems.

This shell program is created exclusively in the [C](https://en.wikipedia.org/wiki/C_(programming_language)) programming language and draws inspiration from the [Thompson Shell](https://en.wikipedia.org/wiki/Thompson_shell).


## Environment :

The shell program was developed and tested on Ubuntu 20.04.

## Features
This shell has the following features:

* Display a prompt and wait for the user to type a command. A command line always ends with a new line.
* If an executable cannot be found, print an error message and display the prompt again.
* Handle errors.
* Handle the “end of file” condition (Ctrl+D)
* Handle the command line with arguments
* Handle the PATH
* Support the exit features and the exit status
* Handle the Ctrl-C to not terminate the shell
* Handling the command separator `;`
* Handling && and `||` logical operators
* Handle variable replacements `$?` and `$$`
* Handling comments `#`
* Support the history feature
* Support the file input

## Built-in Commands
Our shell has support for the following built-in commands:

* `exit [n]` : Exit the shell, with an optional exit status, n.
* `env` : Print the environment.
* `setenv [var][value]` : Set an environment variable and value. If the variable exists, the value will be updated.
* `alias[name[='value]]` : Reads aliases name
* `unsetenv [var]` : Remove an environment variable.
* `cd [dir]` : Change the directory.
* `help [built-in]` : Read documentation for a built-in.

## Installation:

Clone the repository from GitHub and compile the source files into an executable using GCC compiler.
<sub>[How to clone a repository](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)</sub>
<sub>[How to fork a repository](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo)</sub>

Clone the below repository and compile the files into an executable using the GCC compiler.

```
https://github.com/Chey04/simple_shell
```

Once you have cloned the repository, you can compile the files into an executable using the GCC compiler:

```
gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
```

### Basic Usage 

To use the shell, run the following command:
```
./hsh
```

This will start the shell and display the prompt:
```
$
```

From here, you can enter commands just like in a normal terminal. The shell will interpret and execute the commands, and then display the prompt again.

## Example

Here's an example of how to use the shell:
```
ls -la
```

![ls -la output](https://imgur.com/ZsNFN2L)


:white_check_mark: and Voila! That's it, we have now successfully installed the shell program. The shell program allows you to execute commands and perform various operations in the operating system. To start the shell program, navigate to the directory where the shell program is installed and run the following command:

```
$ ./hsh
```
After executing this command, you can start entering the commands you wish to execute in the operating system. The shell program will interpret your commands and execute them accordingly. So, let's get started and perform some amazing operations with our new shell program!

## Contributors :
* [**Chinemerem Chukwukere**](https://github.com/Chey04)
* [**Emeka Emodi**](https://github.com/emmy3000)

## Acknowledgments :

We are grateful for the opportunity given to us by Holberton School | Alx-Africa to work on this project. We would like to recognize the contributions of the creators of the C language, whose work has had a profound impact on the field of computer science. It has been an honor to work on this project, and we hope that it will make a meaningful contribution to the community. Thank you for taking the time to read through our README.md file, and we look forward to sharing more updates with you in the future.
