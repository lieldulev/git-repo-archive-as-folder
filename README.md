# git repo archive as folder
  
This is a bash script to merge a branch from a remote repo into a directory of another remote repo *while keeping the commit history*.
> **Important Note**
>
> The destination repository will have more than one root commit, but usually that shouldn't pose a problem.  
> (Based on: http://stackoverflow.com/a/20974621/5759805)

## 3 Step Installation

`gitrepoarc` is just a BASH shell script.

1. Grab (download, copy/paster, clone) `gitrepoarc` and put it somewhere that is included in your PATH.
2. If it isn't marked as executable, type  `chmod +x gitrepoarc` to make it so.
3. I lied, there is no 3rd step. 

## Usage
```
  gitrepoarc SOURCE_REPO DESTINATION_REPO DESTINATION_FOLDER SOURCE_NAME [SOURCE_BRANCH]
```
The SOURCE_REPO will be "copied" to DESTINATION_REPO / DESTINATION_FOLDER / SOURCE_NAME
> **If SOURCE_BRANCH not specified `master` branch will be copied.**

## Options
```
  -h --help  Displays usage information.
```

## License
None. Public Domain. Do whatever you want.

## Warranty
None. Don't come looking for me.
