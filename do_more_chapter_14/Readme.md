
# Chapter 16: Wildcard Matching

## Do More

### Clean up everything in temp from all the exercises so far

    Stefans-MacBook-Pro:~ $ cd temp/
    
    
    Stefans-MacBook-Pro:temp $ ls
    adirectory        iamcool.txt       r.txt             thefourthfile.txt
    bdirectory        neat.txt          run               touch_directory
    ex12.txt          newplace          s.txt             uncool.txt
    ex13.txt          q.txt             something
    
    
    Stefans-MacBook-Pro:temp $ rm uncool.txt
    
    
    Stefans-MacBook-Pro:temp $ ls
    adirectory        iamcool.txt       r.txt             thefourthfile.txt
    bdirectory        neat.txt          run               touch_directory
    ex12.txt          newplace          s.txt
    ex13.txt          q.txt             something
    
    
    Stefans-MacBook-Pro:temp $ rm iamcool.txt neat.txt thefourthfile.txt
    
    
    Stefans-MacBook-Pro:temp $ ls
    adirectory      ex13.txt        r.txt           something
    bdirectory      newplace        run             touch_directory
    ex12.txt        q.txt           s.txt
    
    
    Stefans-MacBook-Pro:temp $ cp -r something newplace
    
    
    Stefans-MacBook-Pro:temp $ rm something/awesome.txt
    
    
    Stefans-MacBook-Pro:temp $ rmdir something
    
    
    Stefans-MacBook-Pro:temp $ rm -rf newplace
    
    
    Stefans-MacBook-Pro:temp $ ls
    adirectory      ex12.txt        q.txt           run             touch_directory
    bdirectory      ex13.txt        r.txt           s.txt
    
    
    Stefans-MacBook-Pro:temp $ rm -rf adirectory
    
    
    Stefans-MacBook-Pro:temp $ rm -rf bdirectory
    
    
    Stefans-MacBook-Pro:temp $ rm -rf run
    
    
    Stefans-MacBook-Pro:temp $ rm -rf touch_directory
    
    
    Stefans-MacBook-Pro:temp $ ls
    ex12.txt ex13.txt q.txt    r.txt    s.txt
    
    
    Stefans-MacBook-Pro:temp $ rm ex12.txt ex13.txt q.txt r.txt s.txt
    
    
    Stefans-MacBook-Pro:temp $ ls
    
    
    Stefans-MacBook-Pro:temp $
    
    
    
    
    
    
### Write in your notebook to be careful when running recursive remove on files

   I have to be careful when running recursive remove on files because the command __rm -rf__ without a specified directory after it, would erase all the files on my computer. Recursive remove is useful because a directory with files inside can't be removed otherwise, unless the user goes into the directory first and removes the files. This way it's faster, but it's also risky.

