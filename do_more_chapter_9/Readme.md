
# Chapter 9: Making Empty Files (Touch)

## Do More

### Make a directory, change to it, and then make a file in it. Then change one level up and run the rmdir command in this directory. You should get an error. Try to understand why you got this error.

    Stefans-MacBook-Pro:temp $ mkdir touch_directory
    
    
    Stefans-MacBook-Pro:temp $ cd touch_directory
    
    
    Stefans-MacBook-Pro:touch_directory $ touch newfile.txt
    
    
    Stefans-MacBook-Pro:touch_directory $ cd ..
    
    
    Stefans-MacBook-Pro:temp $ rmdir touch_directory/
    rmdir: touch_directory/: Directory not empty

* The reason this directory cannot be removed is because it is not empty, it has a file.
