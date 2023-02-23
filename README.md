<h1 align="center"> A Simple shell program created with C </h1>

----------------------------------------------------------

<h2> Table of Content </h2>
* [Description](#description)
* [Purpose](#purpose)
* [Requirements](#requirements)
* [File Structure](#file-structure)
* [Usage](#usage)
* [Examples](#examples)
* [Bugs](#bugs)
* [Authors](#authors)
* [License](#license)

##Description 
A simple UNIX command interpreter that replicates functionalities of the simple shell (sh). Additional functions are also included. This program was written entirely in C as a milestone project for ALX Africa Software Engineering.

##Purpose
The purpose of the simple shell project is to understand:
* how a shell works
* PID and PPIDs
* how processes are created
* the three prototypes of `main`
* how the shell uses the `PATH` to find and execute programs
* the `EOF`/"end-of-file" condition

## Requirements

* Must follow [Betty](https://github.com/holbertonschool/Betty/wiki) style and document guidelines
* Allowed editors: `vi`, `vim`, `emacs`
* Must have a `README.md` file
* All header files must be include guarded
* No more than 5 functions per files

## Compilation

```gcc -Wall -Wextra -Werror -pedantic *.c -o hsh```

## Compilation

```gcc -Wall -Wextra -Werror -pedantic *.c -o hsh```

*GCC 4.8.4 or later only*

## Usage Examples

### Interactive Mode

```c
~/me$ ./hsh
($) pwd
/
($) exit
~/me$
```

### Non-Interactive Mode

```c
~/me$ cat shell.txt
got me feelin' my newly created shell so let's just keep on coding'
~/me$
```

## Authors

Emmanuel Adetoro | [GitHub](https://github.com/adegboyega96) | [Twitter](https://twitter.com/adegboyega95)
Mary Okonkwo | [GitHub](https://github.com/) | [Twitter](https://twitter.com/)
