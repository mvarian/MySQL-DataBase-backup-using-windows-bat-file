# One Click Automatic Backup All Your MySQL Database in zip format Using Windows Batch file
* Use this to Backup all of your MySQL databases on your local WAMPServer machine or MySQL Database host.
* It will create flat backup files in separate sql files using mysqldump, and then compress them into password protected 7zip archives.
* It will also automatically prune the backup directory of any backups beyond a certain age, so that directory can be managed to not take up too much space.
* You can also automate the execution of this script using Windows Task Scheduler.

## How to Use
1. To do this you will need to create a *.bat file (using notepad). Open up notepad and copy and paste the script below.
2. You will require to change the dbUser, dbPassword, backupDir, mysqldump, mysqlDataDir, backupPassword, maxBackupAgeDays, and zip file/app locations.
3. Save the file as mysqlbackup.bat
4. This script will now be executable. Go to your command prompt and run this to backup your databases.

Find more at http://www.proy.info/one-click-automatic-backup-all-your-mysql-database-in-zip-format-on-windows/
