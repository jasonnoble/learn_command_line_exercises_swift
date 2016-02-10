
# Chapter 12: View a File (less, more)

## Do More

### Open your text file again and repeatedly copy-paste the text so that it's about 50-100 lines long.

Ok

### Copy it to your temp directory again so you can look at it.

`cp ~/Desktop/blah.txt blah/`
`more blah/blah.txt`

### Now do the exercise again, but this time page through it. On Unix you use the spacebar and w (the letter w) to go down and up. Arrow keys also work. On Windows just hit spacebar to page through.

Awesome!

### Look at some of the empty files you created too.

`less ../chapter_5/Readme.md`

`less ../chapter_10/blah/blah.txt`

### The cp command will overwrite files that already exist so be careful copying files around.

I was careful.
    
## English Questions

### Can we see what's in our production log?

`more log/production.log`

### What does our database.yml look like?

`less config/database.yml`
