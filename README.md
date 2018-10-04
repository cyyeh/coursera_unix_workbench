# The Unix Workbench

## Week 1 Unix and Command Line Basics

**Learning Objectives**

1. Describe Unix
2. Install and/or access Bash
3. Execute basic commands in the command line
4. Create and manipulate directories
5. Inspect, move, copy and delete files and folders

### Describe Unix

Unix is an operating system and a set of tools. In this course we'll be using the most is shell, a computer program that provides a command line interface.

### Install and/or access Bash

Turn on terminal

### Command Line Basics

- command format:
`[command] [options] [arguments]` where options are usually preceded by a hypehn(`-`) and they tweak the behavior of the command. Arguments can be names of files, raw data, or other options the command requires.
- type command line commands after the prompt(`ChihYude-MacBook-Pro:~ chihyu$`)
- `clear`: clean up your terminal
- `echo`: prints text to your terminal
- You can scroll through command line history with the up and down arrow keys
- `pwd`: print working direcoty (current directory)
- `cd [dir]`: change working directory, if `[dir]` is omitted, then you will go to home directory(`~`)
- `cd /`: go to root directory
- `cd ..`: go to directory before working directory
- `ls`: list files and folders in working directory
- `ls -l`: get a long listing of files in a directory
- `mkdir`: make a directory
- `touch [file_name]`: create a blank file
- `wc [file_name]`: count lines/words/characters in a file
- `cat [file_name]`: print text files to terminal/concatenate files
- `less [file_name]`: view multi-page files, `spacebar` to go next page, and the `b` key to go to previous page, `q` to quit
- `head -n [num] [file_name]`: print top `[num]` lines of file
- `tail -n [num] [file_name]`: print bottom `[num]` lines of file
- `echo [str] > [file_name]`: add `[str]` to `[file_name]`
- `echo [str] >> [file_name]`: append `[str]` to `[file_name]`
- `nano [file_name]`: simple text editor
- `mv [file_name] [dir]`: move files into another directory
- `mv [file_name] [file_name_new]`: rename file
- `cp [file_name] [dir`: copy files into another directory
- `cp -r [dir] [dir_new]`: copy files/directories
- `rm [file_name]`: remove file(**You should try to avoid using rm which permanently removes files or folders**)
- `rm -r [dir]`: remove directory(**You should try to avoid using rm which permanently removes files or folders**)