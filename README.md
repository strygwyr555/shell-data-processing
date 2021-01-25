# Shell Data Processing

## Basic Powershell Commands
- cd - Sets the current working location to a specified location.
- cp - Copies an item from one location to another.
- rm, rmdir - Deletes the specified items.
- mv - Moves an item from one location to another.
- ni - Creates a new item.

## Basic GitBash Commands
- ls - lists your files in current directory.
- touch "filename" - creates or updates (edit) your file.
- rm "filename" - removes a file
- cp "filename" "dest" - copies a file
- mv "filename" "dest" - moves a file to destination

### The curl command used to get your data and write in a file
`curl "yourlongurl" -O "data.txt`

### The command you used to find the most common words, sorted.
`tr ' ' '\12' < data.txt | sort | uniq -c | sort -nr`
