# GIT CHEAT SHEET

## OVERVIEW
This git cheat sheet provide a quick overview of most important ans used git command.
## SETUP
Define user informations used for all local repositories
```cmd
$ git config --global user.name "[firstname lastname]"
$ git config --global user.email "[valid-email]"
$ git config --global color.ui auto // set automatic command line coloring for git
```

## INITIALIZE / CLONE
Itnitialize or clone a repository.
```cmd
$ git init [directory] // directory is facultative
$ git clone [url]
```

## STAGE
```cmd
$ git status // show modified file in working directory
$ git add [file] // stage a file
$ git reset [file] // unstage a file and keep changes
$ git diff // show diff of all changes (not stage)
$ git diff --staged // show diff of all changes (stage)
```

## COMMIT
```cmd
$ git commit -m "[descriptive message]"
```

## BRANCH
```cmd
$ git branch // list your branches and identify currently used branch
$ git branch [branch-name] // create a new branch
$ git checkout [branch-name] // switch to an existing branch
$ git checkout -b [branch-name] // create a new branch and switch to that branch
$ git log // show all commits in the current branch's history
```

## MERGE
```cmd
$ git merge [branch] // merge the specified branch in the current branch
```

## OTHER
Need more? See these links:<br>
[Git Documentation](https://git-scm.com/doc)<br>
[GitHub Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)<br>
[Atlassian Cheat Sheet](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet)<br>
