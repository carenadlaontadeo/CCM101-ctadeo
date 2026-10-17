# Laboratory 09 - Cloud Automation Engineer

## Mission Overview

In this laboratory activity, I learned how to automate tasks in a Linux environment using Bash shell scripting and Cron scheduling. I created a sample application data directory, wrote a backup script, and configured a scheduled task to run the script automatically every day at 2:00 AM.

## Objectives

- Understand the fundamental syntax of a Bash shell script, including variables and basic commands.
- Use the Nano command-line text editor to write and save executable scripts.
- Modify Linux file permissions using the `chmod` command.
- Understand task scheduling and the syntax of a Linux crontab.
- Document automation code and Cron job configurations using Markdown.
- Complete the final chapter of the GitHub Cloud Computing Portfolio.

## Commands Executed

| Command | Purpose |
|---|---|
| `mkdir app-data` | Creates the application data directory. |
| `echo "This is critical client data." > app-data/data.txt` | Creates a sample data file. |
| `nano backup.sh` | Opens Nano to create the Bash script. |
| `./backup.sh` | Attempts to execute the backup script. |
| `chmod +x backup.sh` | Adds execute permission to the script. |
| `ls -l backups/` | Checks the generated backup files. |
| `crontab -l` | Displays the configured Cron jobs. |
| `env EDITOR=nano crontab -e` | Opens the Cron table using Nano. |

## Skills Learned

- Bash shell scripting and variables
- Linux file and directory management
- File permissions and script execution
- File compression and automated backups
- Cron job scheduling
- Technical documentation using Markdown
- GitHub portfolio management
