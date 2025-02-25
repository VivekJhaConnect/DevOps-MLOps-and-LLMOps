### Merge Code to the Branch
**Day 1-3: Working with Branches**

- Creating and switching branches (git branch, git checkout)
- Merging branches (git merge)
- Resolving merge conflicts

**Day 4-5: Introduction to GitHub**

- Creating a GitHub account and repository
- Cloning a remote repository (git clone)
- Connecting local repo to GitHub (git remote)

**Day 6-7: Push, Pull, and Fetch**

- Pushing changes (git push)
- Pulling from remote (git pull)
- Fetching changes (git fetch)

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

