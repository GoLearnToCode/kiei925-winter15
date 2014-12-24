# Setting up your Ruby on Rails development environment

In KIEI-925, we'll be learning the basics of web application development using the Ruby on Rails framework.

Before you begin, make sure that:

- You have a Github account and have installed the Github app
- You have Sublime Text 3 installed

(If you're using the same computer you used for KIEI-924, you're already set)

Then, follow the instructions below, based on your platform.

# For Mac Users

Step 0! Make sure that your Mac is running Mac OS X 10.9 (Mavericks) or later. **If it isn't, please upgrade before continuing.**

Remember Terminal? The application on your Mac that allows you to type command-line instructions? (It's at Applications -> Utilities -> Terminal)... open it up.

### Install Homebrew

Homebrew is a command-line tool that allows for easy installation of software packages from source. It comes with a straightforward one-line install script. If it asks you to install Xcode command-line tools, say yes.

In Terminal, copy-and-paste the following line and hit return:

    ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    
### Install Ruby on Rails

In Terminal:

    \curl -sSL https://get.rvm.io | bash -s stable --rails

Yes, you need that whole line, including the backslash at the beginning. This takes a while, so grab your favorite frosty beverage for this one.

If everything goes well, you should be able to issue the following command:

    rails -v
    
And get back something like:

    Rails 4.2.0
    

