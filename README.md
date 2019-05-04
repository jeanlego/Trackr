# Trackr

This is a utility to do time tracking and report weekly hours, commit, and overall PRs closed and open

create a .passwd file in the root dir of this repository to automate HTTP GET to github api

exmaple
```
myuser
mypasswrd
```

adjust .track to suit your own needs

one absolute path to a repo per line

## usage

```
./punch in    create punch in timestamp
./punch out   create punch out timestamp
./punch get_week  get the weekly report
```
