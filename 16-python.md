### Python
---
MacOS, like Linux, ships with [Python](https://www.python.org/) already installed. But you don't want to mess with the system Python (some system tools rely on it, etc.), so we'll install our own version(s). There are two ways to install Python, (1) `Homebrew` and (2) `Pyenv`. If you plan to use multiple versions of Python (e.g. 2, 3, and anaconda) then you should use `pyenv`.


#### Installation
##### Python 3

```
brew install python
```

##### Python 2.7
```
brew install python@2
```

>Installing Python also installs `pip` (and its dependency `Setuptools`), which is the package manager for Python.

