Day 5 – File Management Commands
history
history --> shows previously used commands.
up arrow or !! --> executes the most recent command again.
Ctrl-R --> start typing any part of the command you're looking for, and the shell will display the most recent match.
history -c linux --> This removes all entries from the history list in memory.
.bash_history --> where history lives
history -w --> force save history
history -d <offset> --> Deleting a Specific Entry.
#The offset is the number shown next to the command in the history output# 
clear --> wipe your display and start with a fresh screen.
cp(COPY) command 
cp [SOURCE] [DESTINATION]--> used for copying files in directories. 
*: Matches any sequence of characters.
?: Matches any single character.
[]: Matches any one of the characters enclosed in the brackets.
-i --> prompts for confirmation before overwriting.
-r --> Used to copy a directory, all of is contents, including sub-directories 
mv(MOVE) 
mv --> Renaming files or directories and moving them to a different location.
-i (interactive)--> confirmation before overwriting any existing file.
-b (backup)--> If you intend to overwrite a file but want to keep the old version, this option creates a backup of the destination file. The backup is typically renamed with a tilde (~) suffix.
-v (verbose)--> This option makes the mv command print out what it is doing, showing each file being moved or renamed.


