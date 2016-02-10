
# Chapter 9: Making Empty Files (Touch)

## Do More

### Make a directory, change to it, and then make a file in it. Then change one level up and run the rmdir command in this directory. You should get an error. Try to understand why you got this error.

`mkdir blah`
`touch blah.txt`
`cd ..`
`rmdir blah`

    Jasons-iMac:chapter_9 jasonn$ rmdir blah
    rmdir: blah: Directory not empty
    Jasons-iMac:chapter_9 jasonn$
    
I think the directory has "something" in it, that's why I can't remove it.

## English Questions

### Can you touch blah.txt?

Sure!  `touch blah.txt`

### Let's create foo.txt.

Sure.  `touch foo.txt`

### What happens if you touch an existing file?

It looks like the file modified time changes.
