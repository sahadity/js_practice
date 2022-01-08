# js_practice
scripts for js practice

# Setup
## node installation
[setup node on windows](https://docs.microsoft.com/en-us/windows/dev-environment/javascript/nodejs-on-windows)

# nmp setup
[setup npm packages](https://www.npmjs.com/)

# Linux Command

```
cd -hange directory
cd .. - go up directory
ls - list all the files
ls -la -ist all the files including hidden files
touch <file_name.ext> - create a new file
mkdir <dir_name> - create a new directory
rmdir <dir_name> - delete an empty directory
rm -d <dir_name> - delete an empty directory
rm - r <dir_name> - delete non-empty directory
cat <myfile.txt> - display file content to screen without limits

```

# Git Command
```
ssh -v git@github.com -> check connectivity between local git and remote git
git config --global user.name "user_name" -> change the user name to the git
git config --global user.email "email_id" -> change the email id to the git
git config --list -> list all the sitting of git
git init -> initialized empty Git repository
git clone [url] -> used to obtain a repository from an existing URL
git status -> lists all the files that have to be committed.
git add [file] -> adds one or more to the staging area.
git commit -m “[message]” -> records or snapshots the file permanently in the version history.
git log -> list the version history for the current branch.
git branch -> lists all the local branches in the current repository.
git branch [branch name] -> creates a new branch.
git branch -d [branch name] -> deletes the feature branch.
git checkout -> used to switch from one branch to another.
git checkout -b [branch name] -> creates a new branch and also switches to it.
git pull -> fetches and merges changes on the remote server to your working directory.

```

# npm packages usage
## how to use express in project
### syntex

```
const express = require("express");
const path = require("path");  // for path setup

const app = express(); 
app.use(express.urlencoded({ extended: true })); // middleware function in Express

app.get("/", function (req, res) {
    res.sendFile(path.join(__dirname, "src/ui/form.html"));
  });
```

