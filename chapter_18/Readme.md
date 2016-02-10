
# Chapter 18: Looking inside files (grep)

## Do More

### Use quotes to find "new file" and "old file" and "This is".

`grep "new file" *`
`grep "old file" *`
`grep "This is" *`

### Take the list of videos you created (or any other list) and use it to find some videos you want to find.

`grep -i swift /tmp/videos.txt`

### Unix: You can use -i to ignore case with grep. Try grep -i new *.txt

I tried it, I liked it.

## English Questions

### Show me the lines in foo.txt that have "ERROR" in them.

`grep ERROR foo.txt`

### Show me the lines in bar.txt that have "davinci" in them.

`grep davinci bar.txt`

### Can you print all the lines in text files that have your first and last name in them?

`grep "Jason Noble" *.txt`
