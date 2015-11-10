# Chrome Kiosk Launchd Scripts

Start Chrome in fullscreen mode

```sh
$ cd ~
$ cd Library/LaunchAgents
$ open .
```
Now, copy `com.unswornindustries.chromekiosk.plist` to here.

```sh
$ sudo chown naturum:staff com.unswornindustries.chromekiosk.plist
$ chmod og-wx com.unswornindustries.chromekiosk.plist
$ launchctl load com.unswornindustries.chromekiosk.plist
```
