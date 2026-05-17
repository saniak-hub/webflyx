#Learning Git

## Command in git
- Porcelain commands 
- Plumbing commands

```bash
git add <file name> # add a file
git add  . # add all file in the current dir

git log [-n 1] to list the commits
git cat-file -p <hash> to concatenate files

```
Check the status of the files `git status` 

Git stores dir as `tree` and file as `blob`


## Config
```bash
git config subcommand -flag section.key value
```
- subcommand
    - `set` to add or update key/value
    - `unset` to remove value
- flag 
    - `--global` sets the configuration global, stores in ~/.gitconfig
    - `--local` stores config with the current dir of the git

# Branching
Renaming a branc
```bash
git branch -m oldername newname

#creating a branch
git branch new_branch


# creating a switching to the new branch add -c flag
git switch -c my_new_branch

# deleting a branch
git branch -d branch_name
```
