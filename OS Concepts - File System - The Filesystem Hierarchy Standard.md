# The Filesystem Hierarchy Standard

- `/bin` contains binaries or user executable files which are available to all users
- `/sbin` contains applications that only the superuser (hence the initial "s") will need
- `/boot` contains files required for starting  your system
- `/home` is where you will find your users home directories. Under this directory there is another directory for each user, if that particular user has a home directory.
- root has its home directory separated from the rest of the users home directories and is `/root`
- `/dev` contains device files
- `/etc` contains most, if not all system-wide configuration files
- `/lib` contains shared library files used by different applications
- `/media` is used for external storage will be automatically mounted
- `/mnt` is like `/media` but its not used very often these days
- `/tmp` contains temporary files, usually saved there by applications that are running. Non-priviliged users may also store files here temporarily.
- `/proc` is a virtual directory. It contains information about your computer hardware, such as information about your CPU, RAM, or Kernel. The files and directories are generated when your computer starts, or on the fly, as your system is running and things change. 
- `/sys` contains information about devices, drivers, and some kernel features. 
- `/srv` contains data for servers
- `/run` is a temporary file system which runs in RAM.
- `/usr` contains many other subdirectories binaries files, shared libraries and so on. On some distributions like CentOS many commands are saved in `/usr`/bin and `/usr`/sbin instead of `/bin` and `/sbin`.
- `/var` typically contains variable-length files such as logs which are files that register events that happen on the system. 