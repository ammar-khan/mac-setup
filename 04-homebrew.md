### Homebrew
---
Homebrew is a free and open-source software package management system that simplifies the installation of software on Apple's operating system, macOS, as well as Linux. 

#### Repository
https://www.github.com/Homebrew/brew

#### Prerequisite 
Before installing Homebrew you need to have the Command Line Tools for Xcode installed.

#### Installation
To install Homebrew run the following in a terminal.

For High Sierra , Sierra, El Capitan, or earlier:
```
/user/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
For Catalina, Mojve, Big Sur or latest:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

Execute the following command to determine your shell:
```
echo $0
```
You’ll see either `bash` or `zsh`.

If you’re using ZSH, you’ll open the file `~/.zshrc` in your editor:
```
nano ~/.zshrc
```

If you’re using the Bash shell, you’ll use the file `~/.bash_profile`:
```
nano ~/.bash_profile
```

Once the file opens up in the Terminal window, add the following lines to the end of the file:
```
# Add Homebrew's executable directory to the front of the PATH
export PATH=/usr/local/bin:$PATH
```

If you modified `.zshrc`, execute this command:
```
source ~/.zshrc
```

If you modified `.bash_profile`, execute this command:
```
source ~/.bash_profile
```

#### Initial Setup Checks

Now let’s verify that Homebrew is set up correctly. Execute this command:
```
brew doctor
```
If no updates are required at this time, you’ll see this in your Terminal:

>Your system is ready to brew.

```
brew --version
```
```
brew analytics off
```
```
brew analytics
```
```
brew update
```

#### Uninstall

For High Sierra , Sierra, El Capitan, or earlier:
```
/user/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/uninstall)"
```
For Catalina, Mojve, Big Sur or latest:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/uninstall.sh)"
``` 