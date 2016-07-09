
If you're not already, please go into the checkpoint_4 directory.

    (master) Stefan
    Stefans-MacBook-Pro:learn_command_line_exercises $ cd checkpoint_4

Remove everything in the foo directory using one command

    (master) Stefan
    Stefans-MacBook-Pro:checkpoint_4 $ rm -rf foo

The following questions are about the file color_preferences.txt.

How many lines are there? 1000
   
    (master) Stefan
    Stefans-MacBook-Pro:checkpoint_4 $ cat -n color_preferences.txt

How many teenagers are there? 

    (master) Stefan
    Stefans-MacBook-Pro:checkpoint_4 $ grep -cE "13|14|15|16|17|18|19" color_preferences.txt
    320


    
Copy the lines from color_preferences.txt to a file called teens.txt, but only include the lines where their age is 13-19.
    
    (master) Stefan
    Stefans-MacBook-Pro:checkpoint_4 $ grep -E "13|14|15|16|17|18|19" color_preferences.txt > teens.txt
        
How many teenagers like the color purple?

    (master) Stefan
    Stefans-MacBook-Pro:checkpoint_4 $ grep purple teens.txt  | wc -l
          14
    
