# Backup Script Guide

## 1. Backup Script Code

The following Bash script automatically compresses the `app-data` directory and saves the backup in the `backups` directory.

```bash
#!/bin/bash
# Automated Backup Script for CloudNova Technologies

SOURCE_DIR="app-data"
BACKUP_DIR="backups"
TIMESTAMP=$(date +"%Y%m%d_%H%M%S")

echo "Initiating automated backup..."

# Create the backup directory if it does not exist
mkdir -p $BACKUP_DIR

# Compress the source directory into a tarball (.tar.gz)
tar -czf $BACKUP_DIR/backup_$TIMESTAMP.tar.gz $SOURCE_DIR

echo "Backup completed successfully at $TIMESTAMP!"
```

## 2. File Permissions

The `chmod +x backup.sh` command adds execute permission to the Bash script. This allows the Linux system to run the script using `./backup.sh`.

## 3. Cron Job Configuration

The Cron expression used is:

```bash
0 2 * * * /root/backup.sh
```

This schedule is configured to run the backup script every day at 2:00 AM.

### Cron Time Fields

| Field | Value | Meaning |
|---|---|---|
| Minute | `0` | At minute zero |
| Hour | `2` | At 2:00 AM |
| Day of Month | `*` | Every day of the month |
| Month | `*` | Every month |
| Day of Week | `*` | Every day of the week |
