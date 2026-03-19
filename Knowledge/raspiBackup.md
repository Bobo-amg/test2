
<a href="https://framps.github.io/raspiBackupDoc/introduction.html">Introduction - raspiBackup Documentation</a>

Procedure: 
- if mounted ... unmount existing backup usb stick ... `sudo umount /mnt/DinoWorld_backups`
- mount backup usb stick as /backup ... (see doco link above)
- once raspiBackup has been setup, run the command and ensure exclusions are applied ... `sudo raspiBackup -m detailed -u "\--exclude=/root/.cache/* \--exclude=/home/main/.node-red/node_modules/*"`


