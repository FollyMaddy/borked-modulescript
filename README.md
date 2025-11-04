Copy script in retropie :
```
wget --backups=1 https://raw.githubusercontent.com/FollyMaddy/borked-modulescript/refs/heads/main/borked3ds.sh -x -nd -np -P ~/RetroPie-Setup/ext/RetroPie-Share/scriptmodules/emulators
```

[Version 0.1](https://github.com/FollyMaddy/borked-modulescript/blob/e252e92d180e0cbd1635b03d4f5ce9e4281f2ae5/borked3ds.sh) tests :

- x86_64 with debian Trixie : OK (fresh OS)

- rpi5 (aarch64) with debian Bookworm : seems OK

- rpi5 (aarch64) with debian Trixie : Fails (fresh OS)

[Version 0.2](https://github.com/FollyMaddy/borked-modulescript/blob/164b7deb51c4e16369ba43c0d672cacb52f9ef14/borked3ds.sh) tests :

- x86_64 with debian Trixie : ?

- rpi5 (aarch64) with debian Bookworm : seems OK

- rpi5 (aarch64) with debian Trixie : seems OK
