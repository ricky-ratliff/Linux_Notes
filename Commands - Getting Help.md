# Commands - Getting Help

## MAN Pages

### man command

`$ man [COMMAND NAME]` 

*The man page is displayed*

### Shortcuts

- `$ h` getting help
- `$ q` quit
- `$ enter` show next line
- `$ space` show next screen
- `$ /string` search forward for string
- `$ ?string` search backward for string
- `$ n / N` next/previous appearance of string in search

### Checking if command is shell built-in or executable file

`$ type rm` 

    rm is /usr/bin/rm

*example of output showing rm is an executable binary*

`$ type cd`

    cd is a shell built-in

*excample of output showing cd is a shell built-in*

### Getting help for commands

- `$ help [COMMAND NAME]` 

- `$ [COMMAND NAME] --help`

### Searching for a command, feature, or keyword in all man pages

- `$ man -k uname`
- `$ man -k "copy files"`
- `$ apropos passwd`