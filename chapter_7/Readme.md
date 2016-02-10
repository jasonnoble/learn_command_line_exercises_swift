
# Chapter 7: Remove Directory (rmdir)

## Do More

### Make 20 more directories and remove them all.

`mkdir tmp`
`cd tmp`
`mkdir directory_1`
`cd directory_1`
`mkdir directory_2`
`cd directory_2`
`mkdir directory_3`
`cd directory_3`
`mkdir directory_4`
`cd directory_4`
`mkdir directory_5`
`cd directory_5`
`mkdir directory_6`
`cd directory_6`
`mkdir directory_7`
`cd directory_7`
`mkdir directory_8`
`cd directory_8`
`mkdir directory_9`
`cd directory_9`
...

### Make a single path of directories that is 10 deep and remove them one at a time just like I did above.
### If you try to remove a directory with contents you will get an error. I'll show you how to remove these in later exercises.

`mkdir -p tmp/directory_1/directory_2/directory_3/directory_4/directory_5/directory_6/directory_7/directory_8/directory_9/directory_10`
`cd tmp/directory_1/directory_2/directory_3/directory_4/directory_5/directory_6/directory_7/directory_8/directory_9/directory_10`
`cd ..`
`rmdir directory_10`
`cd ..`
`rmdir directory_9`
`cd ..`
`rmdir directory_8`
`cd ..`
`rmdir directory_7`
`cd ..`
`rmdir directory_6`
`cd ..`
`rmdir directory_5`
`cd ..`
`rmdir directory_4`
`cd ..`
`rmdir directory_3`
`cd ..`
`rmdir directory_2`
`cd ..`
`rmdir directory_1`
`cd ..`
`rmdir tmp`
`cd ..`
    
## English Questions

### Can you remove the tmp directory?

Sure.  `rmdir tmp`

### Let's remove the tmp directory.

Sure.  `rmdir tmp`
