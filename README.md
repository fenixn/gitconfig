# Useful Git Configurations

## Setup
Open up your .gitconfig file in your editor. On Windows 10, this file is usually located at
C:/Users/[YourUser]/.gitconfig

You can also use this shell command to edit your file in your shell no matter what your setup is.
```shell
git config --global --edit
```

## Alias
The .gitconfig in this repository has aliases that should make some git commands more convenient to call. For example, aa is the alias for add all.

So you can run the command below to add all updated files to your commit
```shell
git aa
```

Another example is c which is the alias for commit -m. You can run the command below to commit with a message
```shell
git c "Your commit message."
```

See the .gitconfig file for a list of all aliases and add the ones your like to your .gitconfig file.
