# File Timestamps

#### Every file on Linux has three timestamps:

- The access timestamp or `atime` is the last time the file was read `$ ls -lu`
- The modified timestamp or `mtime` is the last time the contents of the file was modified `$ ls -l` or `$ ls -lt`
- The changed timestamp `ctime` is the last time when some metadata related to the file was changed `$ ls -lc`