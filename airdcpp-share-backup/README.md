# How to configure airdcpp-share-backup

### <ins>Folder to save backups in</ins>
* Type in the path to the folder where you want your backups to be saved.
* Missing path folders will be created automatically if they do not exist.

### <ins>Compress backups to bz2 (much slower, but smaller file)</ins>
* As default the file list will not be compressed (recommended).
* A large share can take more than 15 minutes to compress.
* AirDC do support both xml and bz2 extensions.

### <ins>Your AirDC++ nickname (used in the backup filename)</ins>
* If you want to specify your own nick to be used in the saved file list name,<br>
do it here, or leave it empty for auto-detect.
* If you use more than one nickname, the name of the file list may differ<br>
depending on which hubs you are connected to when the backup starts.

### <ins>Skip these virtual folders (comma-separated)</ins>
* If you do not want to include one or more of your virtual folders you can add them here.
* You will find your virtual folders in ```Settings / Sharing / Shared directories```.
* If you uncheck the ```Show directory tree``` you will see the name in the ```virtual name``` column.

### <ins>Automatically back up on these days (comma-separated)</ins>
* Specify which weekday or weekdays should trigger a backup:<br>
monday, tuesday, wednesday, thursday, friday, saturday and sunday.<br>
* It will check once per day and it will only create one backup file per day.
* If you run ```/sharebackup``` manually, the existing backup file will be replaced.

### <ins>Delete backups older than this many days (0 = never)</ins>
* This will work both for manually and automatically backups.
* Keep in mind that if you set this to ```0``` you can run out of space<br>
if you create a backup every day and you have a large share.

<details><summary>Click to view Configure</summary>

<img width="614" height="682" alt="image" src="https://github.com/user-attachments/assets/89138665-ff6a-4898-b5ff-f792d2776aff" />

</details>
