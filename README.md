# vscode-snippets
Code snippets for VSCode

## How to install
> We need to make sure the snippets folder is empty first if we want to clone this directly.
  
Go to the snippets location and check there is no files:  
```
cd ~/Library/Application\ Support/Code/User/snippets
ls -la
```

If there is an instance of `.DS_Store` lets remove it:
```
rm .DS_Store
```

Now that we have a clean folder we can clone branch `snippets` in here:
```
git clone -b snippets https://github.com/lisandromindel/vscode-snippets.git .
```

> Otherwise if there are any custom snippets there already, it's recommended to checkout the project somewhere else and copy `general.code-snippets` from the cloned repo into this location


Use, enjoy and happy coding!