# Cheat Sheet for git 

## Branch related

```bash
# Shows all remote and local branches
$ git branch
```

```bash
# Shows all the remote branches
$ git branch -r
```

```bash
# Shows all the local branches
$ git branch -a
```

```bash
# Shows all the local or remote branches with aditional information about the last commit
$ git branch -v -a
# or
$ git branch -v -r
```

### Diff

```bash
# See the diff betweetn branches using the double dot notation
$ git diff <branch>..<feature_branch>
```

## Commit related

```bash
# Display the history of commits for the actual branch
$ git log
```
