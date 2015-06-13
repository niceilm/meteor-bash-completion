# Meteor Bash Completion
Bash shell completions for the Meteor command-line utility.

Installing this script makes it possible to use the Tab key to fill in possible completions.

For example: ```meteor ad[Tab]``` completes to ```meteor add```.

# Support
For Meteor 1.1.0.2

# Installation
## Linux
```
sudo wget https://github.com/niceilm/meteor-bash-completion/raw/master/meteor -O /etc/bash_completion.d/meteor
```

## osx
### install bash-completion
```
brew install bash-completion
```

### add bash profile
~/.bash_profile
```
...

if [ -f `brew --prefix`/etc/bash_completion ]; then
. `brew --prefix`/etc/bash_completion
fi

...
```

### download
```
sudo wget https://github.com/niceilm/meteor-bash-completion/raw/master/meteor -O /usr/local/Cellar/bash-completion/1.3/etc/bash_completion.d/meteor
```

# Resouces
* http://iccode.net/bash-completion-for-the-meteor-web-framework/
* https://github.com/meonkeys/meteor-bash-completion

# License
**MIT**