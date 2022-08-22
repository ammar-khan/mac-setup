### Git
---
Git is free and open source software for distributed version control: tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development.

#### Installation
```
brew install git
```

#### Validate the installation
```
git --version
```
```
which git
```
>/usr/local/bin/git

#### Configure Git

Define Git user (should be the same name and email you use for [GitHub](https://github.com/))

```
git config --global user.name "Your Name Here"
git config --global user.email "your_email@youremail.com"
```
>They will get added to your `.gitconfig` file.

>To push code to your GitHub repositories, we will use the recommended HTTPS method. There are also instructions for using SSH. To prevent git from asking for your username and password every time you push a commit you can cache your credentials by running the following command, as described in the [instructions](https://help.github.com/articles/caching-your-github-password-in-git/).

```
git config --global credential.helper osxkeychain
```

#### Uninstall
```
git --version
```

```
which git
```
> copy git path `/usr/local/bin/git`

```
/usr/local/bin/uninstall.sh
```