
This script traverses the current directory and matches files in the index.

I use this to make sure the files in my photo and music collection is healthy.

Use the find-operator to scan other file structures for new files, ignoring file names.
This feature is great for merging files like imported photos etc with the index.

Usage:
 index <index-file> <fast> <find>

index-file (optional): Path to an index file.
fast (optional): Only compare files by file size. Checksums are calculated only for new files.
find (optional): Only print files that are not already in the index.

