## `find`

find . command used to search for files and directories
. currently

`find . -name "*.log"`

`find . -name *.log -mtime -1`


`-name "*.log"`  files that end with .log

`*` whatever name and then ends with log 

`-mtime`: stand for mdification time (in days)

`-1` means less than 1 day ago (i.e., modified witnin the last 24 hour)

find . -name "*.log" -mtime -1

So, you can use / instead of .. It will search in everywhere.

---


