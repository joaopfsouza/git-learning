# Commands

Create brand new reposiories (repos) on your computer

```
git init
```
Copy existing repos from somewhere else to your local computer
```
git clone
```

Check o status of a repos
```
git satus
```

Git clone and change name of local folder

````
git clone https://github.com/udacity/course-git-blog-project blog-project
````

Show all commits SHA
+ --online: Just show SHA plus commit
+ --stat: Show files change plus info about commit
+ -p: show lines modified
````
git log [--oneline |--stat| -p]
````

Show all modified files

````
git show #SHA
````

Remove files git add to staging index

````
git rm --cached #file   
````
Add tag
````
git tag -a v1.0 [#sha]

````

Verify tags

````
git tag
`````

Delete Tag

````
git tag -d v1.0
````


# Comments of Commit

Do commits messages   explaing "what do" never why the changes or how the changes.
Make sure to explain what was changed

## Explain the Why
If you need to explain why a commit needs to be made, you can!

When you're writing the commit message, the first line is the message itself. After the message, leave a blank line, and then type out the body or explanation including details about why the commit is needed 
