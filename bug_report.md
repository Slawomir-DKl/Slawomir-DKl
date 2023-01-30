# Sample bug report

## Id:
1
## Title:
Backuply - Enormous number of days since the last backup
## Description:
1. **Prerequisities:** WordPress site without installed Backuply plugin
2. **Steps to reproduce:**
   - Go to your WordPress dashboard
   - Install the Backuply plugin
   - Go to WordPress Updates section
3. **Actual result:**
Message: "It’s been 19234 days you took a backup, would you like to take a backup with Backuply and secure your website!"
4. **Expected result:**
The number of days should be counted from the day of Backuply installation, not from the beginning of Unix era.
## Browser:
Opera 94.0.4606.76
## Test environment:
working application
## Tested system version:
Backuply v1.0.2
## Additional information:
The bug was fixed (in response to my report) in version 1.0.3 of Backuply