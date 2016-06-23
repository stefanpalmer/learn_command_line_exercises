
# Chapter 18: Looking inside files (grep)

## Do More

### Use quotes to find "new file" and "old file" and "This is".

    Stefans-MacBook-Pro:temp $ grep "old file" *.txt
    oldfile.txt:This is a old file.
    oldfile.txt:This is a old file.
    oldfile.txt:This is a old file.
    
    
    Stefans-MacBook-Pro:temp $ grep "new file" *.txt
    newfile.txt:This is a new file.
    newfile.txt:This is a new file.
    newfile.txt:This is a new file.
    
    
    Stefans-MacBook-Pro:temp $ grep "This is" *.txt
    newfile.txt:This is a new file.
    newfile.txt:This is a new file.
    newfile.txt:This is a new file.
    oldfile.txt:This is a old file.
    oldfile.txt:This is a old file.
    oldfile.txt:This is a old file.

### Take the list of videos you created (or any other list) and use it to find some videos you want to find.

    Stefans-MacBook-Pro:~ $ grep "Mind" SOMEFILE.txt
    Desktop//GOT/A.Beautiful.Mind.2001.1080p.BrRip.x264.YIFY.mkv-muxeddddfdf.mp4

### Unix: You can use -i to ignore case with grep. Try grep -i new *.txt

    Stefans-MacBook-Pro:temp $ grep -i new *.txt
    newfile.txt:This is a new file.
    newfile.txt:This is a new file.
    newfile.txt:This is a new file.

