
# Chapter 6: List Directory (ls)

## Do More

### On Unix, try the ls -lR command while you're in temp.

    Stefans-MacBook-Pro:temp $ ls -lR
    total 0
    drwxr-xr-x  3 nafetsremlap  staff  102 Jun 12 00:29 stuff
    
    ./stuff:
    total 0
    drwxr-xr-x  3 nafetsremlap  staff  102 Jun 12 00:29 things
    
    ./stuff/things:
    total 0
    drwxr-xr-x  3 nafetsremlap  staff  102 Jun 12 00:29 frank
    
    ./stuff/things/frank:
    total 0
    drwxr-xr-x  3 nafetsremlap  staff  102 Jun 12 00:29 joe
    
    ./stuff/things/frank/joe:
    total 0
    drwxr-xr-x  3 nafetsremlap  staff  102 Jun 12 00:29 alex
    
    ./stuff/things/frank/joe/alex:
    total 0
    drwxr-xr-x  2 nafetsremlap  staff  68 Jun 12 00:29 john
    
    ./stuff/things/frank/joe/alex/john:

### Use cd to get to other directories on your computer then use ls to see what's in them.

    Stefans-MacBook-Pro:temp $ cd stuff
    
    
    Stefans-MacBook-Pro:stuff $ ls
    things
    
    
    Stefans-MacBook-Pro:stuff $ cd things
    
    
    Stefans-MacBook-Pro:things $ ls
    frank
    
    
    Stefans-MacBook-Pro:things $ cd frank
    
    
    Stefans-MacBook-Pro:frank $ ls
    joe
    
    
    Stefans-MacBook-Pro:frank $ cd joe
    
    
    Stefans-MacBook-Pro:joe $ ls
    alex
    
    
    Stefans-MacBook-Pro:joe $ cd alex
    
    
    Stefans-MacBook-Pro:alex $ ls
    john
    
    
    Stefans-MacBook-Pro:alex $ cd john

### Update your notebook with new questions. I know you probably have some, because I'm not covering everything about this command.

### Remember that if you get lost, then use ls and pwd to figure out where you are, then go to where you need to be with cd.

