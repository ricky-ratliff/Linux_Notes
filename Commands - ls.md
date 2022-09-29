# Commands - ls

## Usage 

`ls [OPTIONS] [FILES]`
<br><br>

### Listing the current directory

``` sh

ls ~  =>  list the current user home directory

ls .  =>  list the current directory

ls .. =>  list the parent directory


```

### Listing multiple directories

``` sh

ls / ~ /var => list root+user+/var directories

```

### Listing options

``` sh

ls -l => long listing

ls -a => long listing of all files

ls -1 => listing on a single column

ls -d => display info about the directory

ls -h => display size with human readable format

ls -S => list by size

ls -X => list by file extension

ls --hide=PATTERN => hide files matching a pattern from listing

ls -R => list recursively

ls -i => display inode number

du -sh => display the size of a directory and its contents

```