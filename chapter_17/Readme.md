
# Chapter 17: Finding files (find)

## Do More

### Unix: Get your find index card and add this to the description side: "find STARTDIR -name WILDCARD -print". Next time you drill make sure you can say that phrase so you remember how find is formatted.

`find STARTDIR -name WILDCARD -print`

Find files, starting in the STARTDIR that match the pattern WILDCARD, then print the name of the file.

### You can put any directory where the . (dot) is. Try another directory to start your search there.

`find /tmp -name *.log`

### Look for all the video files on your computer starting at the home drive and use the > to save the list to a file. Remember how you can do SOMECOMMAND > SOMEFILE.txt and it will write the output of SOMECOMMAND to the file SOMEFILE.txt?

`find / -name *.mov -print > /tmp/all_movies.txt`
    
## English Questions

### Can you show me all the files in slash temp slash foo?

`find /tmp/foo`

### What log files are in your log directory?

`find log/`

### Find all the files in the class directory

`find .` in the class directory...

https://gist.github.com/jasonnoble/e3a6181ac3199d1b1d4e
