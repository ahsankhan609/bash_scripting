# BASH Scripting

It was made in 1989. It's a LINUX SHELL just a command line in Linux, which helps us to interact with LINUX operating system. It is a command language interpreter that executes commands read from the standard input device (keyboard) or from a file. It is a command processor that typically runs in a text window where the user types commands that cause actions.

it helps us to do different things like:

1. make new files, deleting, editing them, etc.
2. add new users, deleting them, adding them to user_groups, etc.

## SHELL Commands

### find users' default SHELL

```bash
which $SHELL
echo $SHELL
```

### echo Hello World

we use this command to say computer to print something on the screen. it is used to display a line of text/string that is passed as an argument.

```bash
echo "Hello World"
```

### writing first BASH script - See different methods to run script - make it executable

sometimes we need to automate things, so we write scripts to do that. A script is a file that contains a list of commands that can be executed by the shell.

the first line that we write in a script is called the shebang line(#!/usr/bin/zsh). It tells the shell which interpreter to use to execute the script. here are multiple reason. when we write scripts in linux, they might be PYTHON scripts, PERL scripts, BASH scripts, etc. so we need to tell the shell which interpreter to use to execute the script.

[Hi Mom Bash Script](himom.sh)

we will execute this script by using the command:

```bash
bash himom.sh
```

there is another way to execute the script. First, we have to make the script executable, and adding executable permissions by using this command:

```bash
chmod +x himom.sh
```

then we can execute the script by using the command:

```bash
./himom.sh
```
