# Commands - The Bash History

## Bash History
 
### Showing the history

`$ history`
 
### Removing a line (ex: 100) from the history

`$ history -d 100`
 
### Removing the entire history

`$ history -c`
 
### Printing the no. of commands saved in the history file (~/.bash_history)

`$ echo $HISTFILESIZE`
 
### Printing the no. of history commands saved in the memory

`$ echo $HISTSIZE`
 
### Rerunning the last command from the history

`$ !!`
 
### Running  a specific command from the history (ex: the 20th command)

`$ !20`
 
### Running the last nth (10th) command from the history

`$ !-10`
 
### Running the last command starting with abc 

`$ !abc`
 
### Printing the last command starting with abc 

`$ !abc:p`
 
### Reverse searching into the history

`$ CTRL + R`
 
### Recording the date and time of each command in the history

`$ HISTTIMEFORMAT="%d/%m/%y %T"`
 
#### Making it persistent after reboot

`$ echo "HISTTIMEFORMAT=\"%d/%m/%y %T\"" >> ~/.bashrc`

*Or*

`$ echo 'HISTTIMEFORMAT="%d/%m/%y %T"' >> ~/.bashrc`