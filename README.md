# Git Sync Command
Shortcut for merging master into develop

Run `git sync` from a clean working tree. It fetches origin, fast-forwards `develop`,
merges `origin/master` (or `origin/main`) into it, pushes `develop`, and returns to
the branch you started on. It never pushes master.

## Install:

Download git-sync to a folder on your PATH and make it executable, i.e:

```
curl -fsSL https://raw.githubusercontent.com/peterjohnhunt/git-sync/HEAD/git-sync -o ~/.local/bin/git-sync
chmod +x ~/.local/bin/git-sync
```
