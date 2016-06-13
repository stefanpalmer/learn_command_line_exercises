
# Chapter 7: Remove Directory (rmdir)

## Do More

### Make 20 more directories and remove them all.

    Stefans-MacBook-Pro:snake $ cd ..
    
    
    Stefans-MacBook-Pro:release $ ls
    snake
    
    
    Stefans-MacBook-Pro:release $ rmdir snake
    
    
    Stefans-MacBook-Pro:release $ cd ..
    
    
    Stefans-MacBook-Pro:question $ ls
    release
    
    
    Stefans-MacBook-Pro:question $ rmdir release
    
    
    Stefans-MacBook-Pro:question $ cd ..
    
    
    Stefans-MacBook-Pro:panther $ ls
    question
    
    
    Stefans-MacBook-Pro:panther $ rmdir question
    
    
    Stefans-MacBook-Pro:panther $ cd ..
    
    
    Stefans-MacBook-Pro:ostrich $ ls
    panther
    
    
    Stefans-MacBook-Pro:ostrich $ rmdir panther
    
    
    Stefans-MacBook-Pro:ostrich $ cd ..
    
    
    Stefans-MacBook-Pro:never $ ls
    ostrich
    
    
    Stefans-MacBook-Pro:never $ rmdir ostrich
    
    
    Stefans-MacBook-Pro:never $ cd ..
    
    
    Stefans-MacBook-Pro:moose $ ls
    never
    
    
    Stefans-MacBook-Pro:moose $ rmdir never
    
    
    Stefans-MacBook-Pro:moose $ cd ..
    
    
    Stefans-MacBook-Pro:lemon $ ls
    moose
    
    
    Stefans-MacBook-Pro:lemon $ rmdir moose
    
    
    Stefans-MacBook-Pro:lemon $ cd ..
    
    
    Stefans-MacBook-Pro:kangaroo $ ls
    lemon
    
    
    Stefans-MacBook-Pro:kangaroo $ rmdir lemon
    
    
    Stefans-MacBook-Pro:kangaroo $ cd ..
    
    
    Stefans-MacBook-Pro:joust $ ls
    kangaroo
    
    
    Stefans-MacBook-Pro:joust $ rmdir kangaroo
    
    
    Stefans-MacBook-Pro:joust $ cd ..
    
    
    Stefans-MacBook-Pro:ice $ ls
    joust
    
    
    Stefans-MacBook-Pro:ice $ rmdir joust
    
    
    Stefans-MacBook-Pro:ice $ cd ..
    
    
    Stefans-MacBook-Pro:house $ ls
    ice
    
    
    Stefans-MacBook-Pro:house $ rmdir ice
    
    
    Stefans-MacBook-Pro:house $ cd ..
    
    
    Stefans-MacBook-Pro:forget $ ls
    house
    
    
    Stefans-MacBook-Pro:forget $ rmdir house
    
    
    Stefans-MacBook-Pro:forget $ cd ..
    
    
    Stefans-MacBook-Pro:grape $ ls
    forget
    
    
    Stefans-MacBook-Pro:grape $ rmdir forget
    
    
    Stefans-MacBook-Pro:grape $ cd ..
    
    
    Stefans-MacBook-Pro:favorite $ ls
    grape
    
    
    Stefans-MacBook-Pro:favorite $ rmdir grape
    
    
    Stefans-MacBook-Pro:favorite $ cd ..
    
    
    Stefans-MacBook-Pro:elephant $ ls
    favorite
    
    
    Stefans-MacBook-Pro:elephant $ rmdir favorite
    
    
    Stefans-MacBook-Pro:elephant $ cd ..
    
    
    Stefans-MacBook-Pro:dirt $ ls
    elephant
    
    
    Stefans-MacBook-Pro:dirt $ rmdir elephant
    
    
    Stefans-MacBook-Pro:dirt $ cd ..
    
    
    Stefans-MacBook-Pro:cat $ ls
    dirt
    
    
    Stefans-MacBook-Pro:cat $ rmdir dirt
    
    
    Stefans-MacBook-Pro:cat $ cd ..
    
    
    Stefans-MacBook-Pro:bounce $ ls
    cat
    
    
    Stefans-MacBook-Pro:bounce $ rmdir cat
    
    
    Stefans-MacBook-Pro:bounce $ cd ..
    
    
    Stefans-MacBook-Pro:art $ ls
    bounce
    
    
    Stefans-MacBook-Pro:art $ rmdir bounce
    
    
    Stefans-MacBook-Pro:art $ cd ..
    
    
    Stefans-MacBook-Pro:temp $ ls
    art
    
    
    Stefans-MacBook-Pro:temp $ rmdir art

### Make a single path of directories that is 10 deep and remove them one at a time just like I did above.

    Stefans-MacBook-Pro:temp $ mkdir -p lately/I/have/been/losing/sleep/dreaming/of/all/the
    
    
    Stefans-MacBook-Pro:temp $ cd lately/I/have/been/losing/sleep/dreaming/of/all/the/
    
    
    Stefans-MacBook-Pro:the $ cd ..
    
    
    Stefans-MacBook-Pro:all $ ls
    the
    
    
    Stefans-MacBook-Pro:all $ rmdir the
    
    
    Stefans-MacBook-Pro:all $ cd ..
    
    
    Stefans-MacBook-Pro:of $ ls
    all
    
    
    Stefans-MacBook-Pro:of $ rmdir all
    
    
    Stefans-MacBook-Pro:of $ cd ..
    
    
    Stefans-MacBook-Pro:dreaming $ ls
    of
    
    
    Stefans-MacBook-Pro:dreaming $ rmdir of
    
    
    Stefans-MacBook-Pro:dreaming $ cd ..
    
    
    Stefans-MacBook-Pro:sleep $ ls
    dreaming
    
    
    Stefans-MacBook-Pro:sleep $ rmdir dreaming
    
    
    Stefans-MacBook-Pro:sleep $ cd ..
    
    
    Stefans-MacBook-Pro:losing $ ls
    sleep
    
    
    Stefans-MacBook-Pro:losing $ rmdir sleep
    
    
    Stefans-MacBook-Pro:losing $ cd ..
    
    
    Stefans-MacBook-Pro:been $ ls
    losing
    
    
    Stefans-MacBook-Pro:been $ rmdir losing
    
    
    Stefans-MacBook-Pro:been $ cd ..
    
    
    Stefans-MacBook-Pro:have $ ls
    been
    
    
    Stefans-MacBook-Pro:have $ rmdir been
    
    
    Stefans-MacBook-Pro:have $ cd ..
    
    
    Stefans-MacBook-Pro:I $ ls
    have
    
    
    Stefans-MacBook-Pro:I $ rmdir have
    
    
    Stefans-MacBook-Pro:I $ cd ..
    
    
    Stefans-MacBook-Pro:lately $ ls
    I
    
    
    Stefans-MacBook-Pro:lately $ rmdir I
    
    
    Stefans-MacBook-Pro:lately $ cd ..
    
    
    Stefans-MacBook-Pro:temp $ ls
    lately
    
    
    Stefans-MacBook-Pro:temp $ rmdir lately

### If you try to remove a directory with contents you will get an error. I'll show you how to remove these in later exercises.

 
        
