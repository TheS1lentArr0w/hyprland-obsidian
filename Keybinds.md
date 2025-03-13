# To find app name to bind
### Option 1
```
grep -i '^Exec=' /usr/share/applications/spotify-launcher.desktop
```
When I initially downloaded it, it was named spotify-launcher
### Option 2
```
❯ which spotify-launcher
/usr/bin/spotify-launcher
```
Then can either use `spotify-launcher` or the full path
