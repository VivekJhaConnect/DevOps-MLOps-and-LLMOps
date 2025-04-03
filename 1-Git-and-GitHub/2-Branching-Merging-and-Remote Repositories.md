### Merge Code to the Branch
**Day 1-3: Working with Branches**

- Creating and switching branches (git branch, git checkout)
     
    Create a new branch
    
    ```Shell
    git branch NewBranch
    ```

    Create a new branch from local repository
    
    ```Shell
    git branch -b NewBranch
    ```
    
    Switch to the new branch
    
    ```Shell
    git checkout NewBranch
    ```

    

- Merging branches (git merge)
    
    Merge the new branch to the current branch
    
    ```Shell
    git merge NewBranch
    ```

**Day 4-5: Introduction to GitHub**

- Creating a GitHub account and repository
    
    Create a new repository
    
    ```Shell
    git clone <repository_url>
    ```
- Cloning a remote repository (git clone)
    
    Clone the repository
    
    ```Shell
    git clone <repository_url>
    ```

- Connecting local repo to GitHub (git remote)
    
    Connect the local repository to GitHub
    
    ```Shell
    git remote add origin <repository_url>
    ```

**Day 6-7: Push, Pull, and Fetch**

- Pushing changes (git push)
    
    Push the changes to the remote repository
    
    ```Shell
    git push origin <branch_name>
    ```

- Pulling from remote (git pull)
    
    Pull the changes from the remote repository
    
    ```Shell
    git pull origin <branch_name>
    ```

- Fetching changes (git fetch)
    
    Fetch the changes from the remote repository
    
    ```Shell
    git fetch origin <branch_name>
    ```

I am stand on My Current Branch. So first CHECKOUT that branch Where want to Merge The Code.

```Shell
git checkout -b NewBranch MergeBranch
```

Add Code from My Current Working branch

```Shell
git checkout CurrentBranchName 'file_path name'
```

Check Code Status and add all the files

```Shell
git status
```

```Shell
git add .
```
If you need to all tha use (.) 

or 

```Shell
git add 'file_path'
```
file single file use file_path

git commit -m "comments..."

