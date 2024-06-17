# Backup Script Bash Scripting Final Project

## Tasks Accomplished

- Checked if the number of arguments provided is correct and validated the given directory paths.
- Assigned target and destination directories to variables and displayed them.
- Generated a current timestamp for the backup file name and created the backup file name with the current timestamp.
- Stored the original absolute path and the absolute path of the destination directory.
- Changed to the target directory.
- Calculated timestamps for the previous and next day.
- Listed files in the target directory and determined which files to back up based on their modification time.
- Created a compressed tar backup of the files modified within the last 24 hours.
- Moved the backup file to the destination directory.
- Created a cron job to run the `backup.sh` file every 24 hours.