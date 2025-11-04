Copy script in retropie :
```
wget --backups=1 https://raw.githubusercontent.com/FollyMaddy/borked-modulescript/refs/heads/main/borked3ds.sh -x -nd -np -P ~/RetroPie-Setup/ext/RetroPie-Share/scriptmodules/emulators
```



Tested on [Version 0.1](https://github.com/FollyMaddy/borked-modulescript/blob/e252e92d180e0cbd1635b03d4f5ce9e4281f2ae5/borked3ds.sh) :

- x86_64 with debian Trixie : OK

- rpi5 (aarch64) with debian Bookworm : OK

- rpi5 (aarch64) with debian Trixie : Fails
