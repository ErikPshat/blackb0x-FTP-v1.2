 __________________________________________________________
| ___.   .__                 __   ___.   _______           |
| \_ |__ |  | _____    ____ |  | _\_ |__ \   _  \ ___  ___ |
|  | __ \|  | \__  \ _/ ___\|  |/ /| __ \/  /_\  \\  \/  / |
|  | \_\ \  |__/ __ \\  \___|    < | \_\ \  \_/   \>    <  |
|  |___  /____(____  /\___  >__|_ \|___  /\_____  /__/\_ \ |
|      \/          \/     \/     \/    \/       \/      \/ |
|__________________________________________________________|


FTP Server 1.2

A threaded, multi-connection FTP server for the Playstation 3.

Changelog:

1.2)
> Fixed auto-exiting when using the PS3 Remote Control instead of a gampad.
> Removed leading "/" from roots
> fixed multiple transfer connection issues for filezilla. More then 1 transfer connection at a time should work.
> Fixed misreported file size for files over 4gb.


1.1b) 
+ Added new mount points: /dev_ms, /dev_sd, /dev_cf, /dev_ps2disc, /devps2disc1
+ Added IP address display for ease of use
+ Added screensaver to darken screen after 1m, reawaken with joysticks
> Fixed bug in relative paths for RNFR_Command (renaming bug)
> Fixed (..) parser to allow filenames with (.)
> Fixed CDUP from root directory bug.

1.0b)
Initial release

Instructions:

- Install the package to PS3
- Open up FTP Client of your choice and connect using your PS3's IP and port 21 while leaving username and password blank.
- Enjoy.

Tested with FileZilla, FlashFXp, CuteFTP, and WinSCP

"The age of miracles is past."

Releases:
10/2/10 - FTP Server 1.2
9/25/10 - FTP Server 1.1b
9/23/10 - FTP Server 1.0b
9/12/10 - LV2Dump 0.7a

-blackb0x
