# Log Archive Tool

A CLI tool to archive and compress logs with timestamp.

## Usage
chmod +x log-archive.sh
./log-archive.sh <log-directory>

## Example
./log-archive.sh /var/log

## Output
- Compressed archive : logs_archive_20240816_100648.tar.gz
- Activity log file  : archive_log.txt

## Real World Use
Run on a cron schedule to automatically archive logs daily
and keep the server disk clean.
