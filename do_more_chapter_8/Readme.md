
# Chapter 8: Moving around (pushd, popd)

## Do More

### Use these commands to move around directories all over your computer.

    Stefans-MacBook-Pro:da.lproj $ pushd /Applications/Google\ Chrome.app/Contents/Resources/da.lproj/
    /Applications/Google Chrome.app/Contents/Resources/da.lproj /Applications/Google Chrome.app/Contents/Resources/da.lproj
    
    
    Stefans-MacBook-Pro:da.lproj $ pushd /Applications/Google\ Chrome.app/Contents/
    /Applications/Google Chrome.app/Contents /Applications/Google Chrome.app/Contents/Resources/da.lproj /Applications/Google Chrome.app/Contents/Resources/da.lproj
    
    
    Stefans-MacBook-Pro:Contents $ pushd /Applications/Google\ Chrome.app/
    /Applications/Google Chrome.app /Applications/Google Chrome.app/Contents /Applications/Google Chrome.app/Contents/Resources/da.lproj /Applications/Google Chrome.app/Contents/Resources/da.lproj
    
    
    Stefans-MacBook-Pro:Google Chrome.app $ pwd
    /Applications/Google Chrome.app
    
    
    Stefans-MacBook-Pro:Google Chrome.app $ pushd
    /Applications/Google Chrome.app/Contents /Applications/Google Chrome.app /Applications/Google Chrome.app/Contents/Resources/da.lproj /Applications/Google Chrome.app/Contents/Resources/da.lproj
    
    
    Stefans-MacBook-Pro:Contents $ pwd
    /Applications/Google Chrome.app/Contents
    
    
    Stefans-MacBook-Pro:Google Chrome.app $ popd
    /Applications/Google Chrome.app/Contents /Applications/Google Chrome.app/Contents/Resources/da.lproj /Applications/Google Chrome.app/Contents/Resources/da.lproj
    
    
    Stefans-MacBook-Pro:Contents $ pwd
    /Applications/Google Chrome.app/Contents
    
    
    Stefans-MacBook-Pro:Contents $ popd
    /Applications/Google Chrome.app/Contents/Resources/da.lproj /Applications/Google Chrome.app/Contents/Resources/da.lproj
    
    
    Stefans-MacBook-Pro:da.lproj $ pwd
    /Applications/Google Chrome.app/Contents/Resources/da.lproj
    
    
    Stefans-MacBook-Pro:da.lproj $ popd
    /Applications/Google Chrome.app/Contents/Resources/da.lproj
    
    
    Stefans-MacBook-Pro:da.lproj $ pwd
    /Applications/Google Chrome.app/Contents/Resources/da.lproj
    
    
    Stefans-MacBook-Pro:da.lproj $ popd
    bash: popd: directory stack empty
    
### Remove the i/like/icecream directories and make your own, then move around in them.

    Stefans-MacBook-Pro:roll $ pushd /Users/nafetsremlap/temp/
    ~/temp ~/temp/run/jump/feel/roll
    
    
    Stefans-MacBook-Pro:temp $ pushd /Users/nafetsremlap/temp/run/jump/feel/roll/
    ~/temp/run/jump/feel/roll ~/temp ~/temp/run/jump/feel/roll
    
    
    Stefans-MacBook-Pro:roll $ pushd
    ~/temp ~/temp/run/jump/feel/roll ~/temp/run/jump/feel/roll
    
    
    Stefans-MacBook-Pro:temp $ pwd
    /Users/nafetsremlap/temp
    
    
    Stefans-MacBook-Pro:temp $ pushd
    ~/temp/run/jump/feel/roll ~/temp ~/temp/run/jump/feel/roll
    
    
    Stefans-MacBook-Pro:roll $ pwd
    /Users/nafetsremlap/temp/run/jump/feel/roll
    
    
    Stefans-MacBook-Pro:roll $ popd
    ~/temp ~/temp/run/jump/feel/roll
    
    
    Stefans-MacBook-Pro:temp $ pwd
    /Users/nafetsremlap/temp
    
    
    Stefans-MacBook-Pro:temp $ popd
    ~/temp/run/jump/feel/roll
    
    
    Stefans-MacBook-Pro:roll $ pwd
    /Users/nafetsremlap/temp/run/jump/feel/roll
    
    
    Stefans-MacBook-Pro:roll $ popd
    bash: popd: directory stack empty
    
### Explain to yourself the output that pushd and popd print out to you. Notice how it works like a stack?

   * __pushd__ switches into another directory, but saves the current working directory to return to easily.
   * __popd__ takes off the last directory that was pushed.

### You already know this, but remember that mkdir -p will make an entire path even if all the directories don't exist. That's what I did very first for this exercise.

    Stefans-MacBook-Pro:temp $ mkdir -p run/jump/feel/roll/crawl/skip/hop/
    
