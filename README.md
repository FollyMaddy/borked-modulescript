Copy script in retropie :
```
wget --backups=1 https://raw.githubusercontent.com/FollyMaddy/borked-modulescript/refs/heads/main/borked3ds.sh -x -nd -np -P ~/RetroPie-Setup/ext/RetroPie-Share/scriptmodules/emulators
```



Tested on :

Version 0 (initial commit) : x86_64 with debian Trixie : OK

Version 0.1 : rpi5 (aarch64) with debian Bookworm : OK

Version 0.1 : rpi5 (aarch64) with debian Trixie : Fails
