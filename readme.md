# Git aliases

Copy these aliases in:

> C:\Users\\[User]\\.gitconfig

```
[alias]
wip = !git add -u && commit -m \"WIP\"
save = !git add -A && git commit -m \"SAVEPOINT\"
undo = reset HEAD^ --mixed
rh = reset --hard
aliases = config --get-regexp alias
co = checkout
cob = checkout -b
branches = branch --list
ca = !git add -A && git commit
f = fetch
ctl = commit --amend --no-edit
```
