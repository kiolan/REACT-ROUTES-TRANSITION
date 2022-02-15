My Dot Files


``` 
# Make a directory:
mkdir ~/bin

# Change into new directory:
cd ~/bin

# Git clone this repo:
git clone git://github.com/alysonla/dotfiles.git

# Create/validate existence for a file called .bashrc:
touch ~/.bashrc

# Add the thing in the quotes to the .bashrc file:
echo ". ~/bin/dotfiles/bashrc" >> ~/.bashrc

# Create/validate existence for a file called .bash_profile:
touch ~/.bash_profile

# Add the thing in quotes below to the .bash_profile file:
echo ". ~/.bashrc" >> ~/.bash_profile

# Run .bash_profile:
. ~/.bash_profile
```

![screen shot 2014-12-05 at 3 22 04