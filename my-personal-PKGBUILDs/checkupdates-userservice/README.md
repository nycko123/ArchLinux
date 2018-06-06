# checkupdates-userservice

### systemctl --user service to automatically find system updates using pacman's 'checkupdate'
```
- checkupdates.service - fetches list of available updates and exports it to '/tmp/checkupdates' file
- checkupdates.timer - runs checkupdates.service on a schedule
- checkupdates.hook - pacman's hook to reset '/tmp/checkupdates' file if `pacman -Syu` is being run between scheduled hours
```
