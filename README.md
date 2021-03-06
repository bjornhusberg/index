This script traverses the current directory and matches files in the index.

Personally, I use it to make sure the files in my photo and music collection is healthy.

Usage:
`index <index-file> <fast> <find>`

`index-file` (optional): 
Path to an index file. Default is <code>index.txt</code> in the current working directory.

`fast` (optional): 
Only compare existing files by file size. This is handy when you just want to add 
new files to the index or when you just want to make a quick check that all
files are there.

`find` (optional): 
Traverses the current working directory in search for files that are not already in the
specified index, *ignoring file names*. This is useful when merging a fileset
into the index and you don't know which files have already been imported - a frequent 
situation in my own somewhat flawed photo management routine.

