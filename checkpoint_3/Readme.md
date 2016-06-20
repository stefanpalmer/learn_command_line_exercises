
If you're not already, please go into the checkpoint_3 directory.

    Stefans-MacBook-Pro:~ $ cd ~/workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises/checkpoint_3

Can you rename foo/bar/file1.txt to foo/blah.txt?

    (master) Stefan
    Stefans-MacBook-Pro:checkpoint_3 $ mv foo/bar/file1.txt foo/blah.txt
    
Let's make a copy of foo/blah.txt and put it in the foo/bar/baz directory.

    (master) Stefan
    Stefans-MacBook-Pro:checkpoint_3 $ cp foo/blah.txt foo/bar/baz/

What happens if you touch an existing file. (Hint:  The answer is not nothing...)

   * It updates the timestamp of the file to the computer's current date and time.

Can you copy the foo/blah.txt file to slash temp?

    (master) Stefan
    Stefans-MacBook-Pro:checkpoint_3 $ cp foo/blah.txt slash temp/
    usage: cp [-R [-H | -L | -P]] [-fi | -n] [-apvX] source_file target_file
           cp [-R [-H | -L | -P]] [-fi | -n] [-apvX] source_file ... target_directory

Can you copy .bash_profile in your home directory to the current directory? (Do not use cd here...)

    Stefans-MacBook-Pro:~ $ cp .bash_profile workspace/davinci_coders_t2_2016/homework/learn_command_line_exercises/checkpoint_3/

What's in foo/blah.txt?

    (master) Stefan
    Stefans-MacBook-Pro:checkpoint_3 $ cat foo/blah.txt
    This is line 1
    This is line 2
    This is line 3
    This is line 4
    This is line 5
    This is line 6
    This is line 7
    This is line 8
    This is line 9
    This is line 10
    This is line 11
    This is line 12
    This is line 13
    This is line 14
    ... 
    This is line 4986
    This is line 4987
    This is line 4988
    This is line 4989
    This is line 4990
    This is line 4991
    This is line 4992
    This is line 4993
    This is line 4994
    This is line 4995
    This is line 4996
    This is line 4997
    This is line 4998
    This is line 4999
    This is line 5000
    
    
Can you show me what's in foo/blah.txt one page at a time?

    (master) Stefan
    Stefans-MacBook-Pro:checkpoint_3 $ less foo/blah.txt
    
    (master) Stefan
    Stefans-MacBook-Pro:checkpoint_3 $ more foo/blah.txt
