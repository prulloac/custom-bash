Custom Bash Appearance


``` 
# Make a directory:
mkdir ~/bin

# Change into new directory:
cd ~/bin

# Git clone this repo:
git clone git://github.com/prulloac/custom-bash.git

# Create/validate existence for .bashrc:
touch ~/.bashrc

# Add the thing in the quotes to the .bashrc file:
echo ". ~/bin/custom-bash/bashrc" >> ~/.bashrc

# Create/validate existence for a file called .bash_profile:
touch ~/.bash_profile

# Add the thing in quotes below to the .bash_profile file:
echo ". ~/.bashrc" >> ~/.bash_profile

# Run .bash_profile:
. ~/.bash_profile
```
