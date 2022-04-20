# terminal-commands
various terminal commands to make life easier


1. clone repo

`git clone git@github.com:barwis/terminal-commands.git folder-name`

2. add the directory to $PATH

`export PATH="/path/to/folder-name/:$PATH"`

3. source `.bashrc` / `.zshrc` / `.whateverrc` or just open new terminal tab/window

Note: remember that path needs to be absolute, so no `~/` in it

4. add executable priviledge to all files in the `folder-name` directory:


```
chmod +x *
```

## TOC:

## 1. `git lazypush`

git commit + git push in one go, because life is too short.

usage:

```git lazypush 'your message'```

---

## 2. `git update`

merges master into current branch

usage:

```git update```

---

## 3. `git branch cleanup`

deletes local branches that no longer exist on remote

usage:

```git branch cleanup```

