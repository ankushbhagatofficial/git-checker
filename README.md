# git-checker
This tool is checking for available git repository updates.

Usage with curl:

```
source <(curl -sLo- git.io/git-check)
git-check -a
```

**for silent usage**
```
git-check -s
```
**working with another directory**
```
git-check -a -d "__dir__"
```
