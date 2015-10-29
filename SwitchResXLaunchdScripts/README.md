# SwitchResX Launchd Scripts

Rotate nicely on startup

```sh
$ cd ~
$ cd Library/LaunchAgents
$ open .
```
Now, copy `rotatetool` and `com.unswornindustries.rotatescreen.plist` to here.

```sh
$ sudo chown naturum:staff com.unswornindustries.rotatescreen.plist
$ sudo chown naturum:staff rotatetool
$ chmod og-wx com.unswornindustries.rotatescreen.plist
$ launchctl load -w -S Aqua com.unswornindustries.rotatescreen.plist
```
