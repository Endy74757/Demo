# Simple backup System
## How to execute files
__STEP1__ :  Open the terminal linux and directory to the ___backup.sh___
>  cd {directory_PATH}

__STEP2__ : Copy the backup.sh script into the ___/usr/local/bin/___ directory.
> sudo cp backup.sh /usr/local/bin/

__STEP3__ : Edit crontable and add ___*/1 * * * * /usr/local/bin/backup.sh {target_directory_PATH} {destination_directory_PATH}___ in crontable with command:
> crontab -e

__STEP4__ : start the cron service using the below command:
> sudo service cron start

__STEP5__ : If you want to stop the cron service using the below command:
> sudo service cron stop
