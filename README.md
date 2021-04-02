# My Sublime Text Settings, Packages & Keymaps

I got the idea of version controlling my Sublime Text settings after reading [this blog post](https://medium.com/@devmount/using-git-to-sync-sublime-text-settings-f70b8dc7a40d#.dl5pzen41).

## TL; DR
Apply these Submlime Text 3 settings by fetching this repository to your local environment. On a Linux (or at least the Debian-based distros) default installation:
```
$ cd ~/.config/sublime-text-3/Packages/User
$ git init
$ git remote add origin https://github.com/zucchivan/sublime-config.git
```
**[STOP]** Back up your settings file first, or remove the `--hard` flag & resolve merge conflicts manually:
```
$ git reset --hard origin/master
```
Restart Sublime Text 3 to apply these settings & install packages.

To keep it in sync once it's configured:
```
$ git -C ~/.config/sublime-text-3/Packages/User pull
```


