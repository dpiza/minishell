# Minishell

![42-Badge](https://img.shields.io/badge/%C3%89cole-42SP-blue)![C-Badge](https://img.shields.io/badge/Language-C-lightgrey)[![42Unlicense](https://img.shields.io/badge/License-42Unlicense-yellowgreen)](https://github.com/gcamerli/42unlicense)![Denny's 42Project Score](https://img.shields.io/badge/Success-110%2F100-brightgreen)

## Description

Minishell is about creating a simple shell, like **bash** or **zsh**.

## Goals

The objective of this project is to create a simple shell. And through that, to learn a lot about processes and file descriptors.

## Mandatory

• Not interpret unclosed quotes or unspecified special characters like **\\** or **;**.

• Not use more than one global variable.

• Show a prompt when waiting for a new command.

• Have a working History.

• Search and launch the right executable.

• It must implement **echo**, **cd**, **pwd**, **export**, **unset**, **env** and **exit**.

• Redirections, Pipes and Environment variables.

• **CTRL+C**, **CTRL+D** and **CTRL+\\**

## Bonus


• The wildcard * should work for the current working directory.


## Usage

To compile the program, run:

```Shell
$ make
```
Open minishell by executing:

```Shell
$ ./minishell
```
Have fun!

## Additional Files

The file [readline.supp](https://github.com/dpiza/minishell/blob/main/suppression/readline.supp) was used to help with the leak check using Valgrind, by hiding all the leaks caused by readline/readline.h and readline/history.h functions.

## Contribution

This was a group project made in partnership with [Rafael Rocha](https://github.com/rkrocha)

## License

This work is published under the terms of [42 Unlicense](https://github.com/gcamerli/42unlicense)