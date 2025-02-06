GIT is a popular version control      system that records the changes made to our code over time in a special database called repository.

# git config
```bash
git config user.name "gdhjhj"
git config user.email "gjhsgj"
```

# to create an ssh key

github settings > ssh and gpg keys > guide to :connecting to github using ssh keys" > scroll till "adding a new ssh key to ssh-agent" > generating a new ssh key and adding it to ssh agent > copy paste the text (not legacy system) to git bash > a .ssh file will be created in main directory > copy and paste contents of public ssh file to "add ssh key" on github 



# to access til repository

```bash
cd 
cd projects
 cd til 
 code .
```

# to create repository

```bash
new repository 
  repository name [private/public; readme(optional)]
```

# to clone repository

-copy SSH url from code dropdown menu

 -in terminal-
   ```bash
   cd projects 
     git clone (url)
  ```

# to add, commit, push

-in VSCode-
  add file (stage changes) > commit > push

-in terminal-
   ```bash  
   cd (file)
    git add .
    git commit -m "commit message"
    git push
   ``` 

# to pull

-commit changes in git editor

  -in terminal-
   ```bash
   cd (file)
     git pull
  ``` 

# to get state of working directory and staging area

```bash
git status
```

# to get back to last comitted position

```bash
git reset
```

