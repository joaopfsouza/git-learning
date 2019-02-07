# git-learning

# Git

Algoritmo de versionamento de código distribuido


## .gitgnore

Exclui do versionamento arquivos específicos    


## Commands

sets up Git with your name
````
git config --global user.name "<Your-Full-Name>"
````

sets up Git with your email
```
git config --global user.email "<your-email-address>"
```

makes sure that Git output is colored
```
git config --global color.ui auto
```

displays the original state in a conflict
```
git config --global merge.conflictstyle diff3
```

```
git config --list

````

# Define Editor default

## Atom Editor Setup
```
git config --global core.editor "atom --wait"
```

## Sublime Text Setup

```
git config --global core.editor "'C:/Program Files/Sublime Text 2/sublime_text.exe' -n -w"

````

## VSCode Setup

````
git config --global core.editor "code --wait"
````