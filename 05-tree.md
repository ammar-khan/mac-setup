### Tree
---
The tree command lets you see a graphical directory tree and is available via Homebrew.

#### Installation
```
brew install tree
```

Verify that tree is installed by displaying the command’s location with the which command:

```
which tree
```

Run the tree command to see the version:
```
tree --version
```

Run the tree command to upgrade:
```
brew upgrade tree
```

#### Usage
```
tree
```

To limit the recursion you can pass an -L flag and specify the maximum depth tree will use when searching.

```
tree -L 1
```