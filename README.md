# vscode-snippets
Code snippets for VSCode

## Snippets
[general.code-snippets](https://github.com/lisandromindel/vscode-snippets/blob/snippets/general.code-snippets)

## How to install
> We need to make sure the snippets folder is empty first if we want to clone this directly.
  
1. Go to the snippets location and check there is no files:  
```
cd ~/Library/Application\ Support/Code/User/snippets
ls -la
```

2. If there is an instance of `.DS_Store` lets remove it:
```
rm .DS_Store
```

3. Now that we have a clean folder we can clone branch `snippets` in here:
```
git clone -b snippets https://github.com/lisandromindel/vscode-snippets.git .
```

> Otherwise if there are any custom snippets there already, it's recommended to checkout the project somewhere else and copy `general.code-snippets` from the cloned repo into this location

Choose a clone location in your directory and do step 3 and copy cloned file into snippets folder:
```
cp general.code-snippets ~/Library/Application\ Support/Code/User/snippets/general.code-snippets
```

Use, enjoy and happy coding!