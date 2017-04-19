# gordutils
Some simple command line file management tools

This little python program was written to help my stepdad clean up his hard drive.  He had copies of copies of files scattered 
everywhere and I wanted to help him eliminate all of the duplicate files.  In addition he had chains of directories (some 
ending in no files) that he wanted flattened out so he could see and work with his files.

I started with a duplicate filename process but soon moved on to using checksums as a more efficient way of eliminating 
duplicates.  Other tools introduced over time included 

1. removing empty directories from a 'base filesystem'
2. copying or moving all files or files of only a particular extension to another directory (or even the same one)
3. removing all files of a particular extension (optionally limited by maximum size)

I'm a bit of a novice at python, this being my first python program.  I've found the available data structures (lists, 
sets, dictionaries) to be perfect for the types of things I'm doing in this program.

Manual available here:  https://docs.google.com/document/d/1WN8mYN2dUhBal6Bdb9weXaAr93ADUgkal72UZ0SVPt0/edit?usp=sharing

