# The Command Line
- I am a CLI Linux user so command line is pretty natural to me, if I would have to make any kind of observation is that for performing simple tasks the CLI is the most productive way to go.
# Basic Navigation
- Basic navigation tools of the trade include , ls, cd cd .., cd~, mkdir, touch "file.name".  All is within standard file tree path structure.
# More About Files
- anything after the . usually sigifies the file type especially in windows.  However file types are not necessarry in linux, it just makes it easier for the user to identify them and for organizational purposes.
# Manual Pages
- Manual pages usually called with -help or -man give a list of possible commands for CLI programs.
# File Manipulation
- Commands cp, mv, and rm are the most commonly used to copy, move or remove files and or folders.  Also you can rename a file or folder by useing the move(mv) command just change the name for the last peramiter.
# Vi Text Editor
- Impossible to exit, have never been a fan.  I prefer the alternatives and mostly use nano if I ever have to modify a file from command line.
# Wildcards
- * selects all possibilities following.
# Permissions
- use sudo (super user do) for admin privliges per command or sudo su to switch to super user mode.  You can also use chmod and chown to change permissions.
# Filters
- Filters remove undesired results from searches.
# Grep and Regular Expressions
- Grep is a more specific method for conducting searches within folders, which is useful with limited screen space for cli text and large file structures.
# Piping and Redirection
- Piping is used to run a program through another program or to perform an extended task beyond the main programs default capabilities.
# Process Management
- I assume this is talking about processes running on the system viewable through top or my personal favorite htop.  There is another one I like written in python called glances
# Scripting
- Scripting is a way of running code without compiling it to machine code.  Javascript, bash scripting, and python are script languages that run through interpriters.  Languages like C C++ and C# run through compilers before they can be used on the system.
# Cheat Sheet
- I think I put most of my cheat sheet commands throught this file.  But here are some honerable mentions.
rm -rf
df -th
du -hs /"path"
du -ch
ln -s /path/to/file /path/to/symlink