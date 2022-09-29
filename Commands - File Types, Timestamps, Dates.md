# Commands - File Types, Timestamps, and Dates

## Display timestamps with the ls command

``` sh

ls -lu => display atime

ls -l => display mtime, sort output by name

ls -l --fulltime => display full timestamp

ls -lt => display mtime, newest files first

ls -ltu => display and sort by atime

ls -ltu --reverse => display and sort by atime in reverse order

ls -lc => display ctime

```

## Display timestamps with the stat command

``` sh

stat file.txt => display all timestamps

```

## Manipulate timestamps with the touch command

``` sh

touch file.txt => create new file or update timestamps on existing file

touch -a file => change the atime to the current time

touch -m file => change the mtime to the current time

touch -m -t 201812301530.45 a.txt => change the mtime to a specific date and time

touch -d "2010-10-31 15:45:30" a.txt => change both atime and mtime to a specific date and time

touch a.txt -r b.txt => change the timestamp of a.txt to that of b.txt

```

## Display and modify the date and time

``` sh

date => display the date and time

cal => display this months calendar

cal 2021 => display the calendar of a specific year

cal 7 2021 => display the calendar of a specific month/year

cal -3 => display the calendar of last month/current month/next month

date --set="2 OCT 2020 18:00:00" => set the date and time


```