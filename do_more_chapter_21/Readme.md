
# Chapter 21: What's in your Environment (env, echo)

## Do More

### I want you to go online and research how you change your PATH for your computer. Try to do it entirely from the CLI.

    (master) Stefan
    Stefans-MacBook-Pro:temp $ echo $PATH
    /Users/nafetsremlap/.rvm/gems/ruby-2.3.1/bin:/Users/nafetsremlap/.rvm/gems/ruby-2.3.1@global/bin:/Users/nafetsremlap/.rvm/rubies/ruby-2.3.1/bin:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/Users/nafetsremlap/.rvm/bin
    
    (master) Stefan
    Stefans-MacBook-Pro:temp $ PATH=$PATH\:/dir/path ; export PATH
    
    (master) Stefan
    Stefans-MacBook-Pro:temp $ echo $PATH
    /Users/nafetsremlap/.rvm/gems/ruby-2.3.1/bin:/Users/nafetsremlap/.rvm/gems/ruby-2.3.1@global/bin:/Users/nafetsremlap/.rvm/rubies/ruby-2.3.1/bin:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/Users/nafetsremlap/.rvm/bin:/dir/path
