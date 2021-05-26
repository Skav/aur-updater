# aur-updater
Simple bash script to update AUR repositories

All you have to do with this script is change this line:  

`aur_directory="/path/to/directory"`

You have to replace `/path/to/directory/*` with yours AUR directory path, but remember about `/*` at the end.

If you want use this script like command, you need to put it on `/usr/bin/` without `.sh` extension

In some cases you may have to change bash path. To change it, you need to write `which bash` in terminal, and change path in `#!/usr/bin/bash` to your bash path

Have a nice day!
