# user-checkupdates

### systemctl --user service file to find system updates using pacman's 'checkupdate'
```
- checkupdates.service - fetches number of available updates and pipes it to '/tmp/checkupdates' file
- checkupdates.timer - runs checkupdates.service on a schedule
- checkupdates.hook - pacman's hook to reset '/tmp/checkupdates' file if `pacman -Syu` is being run between scheduled hours
```
