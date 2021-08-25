## Auto Deploy on Shared Hosting
thanks for tutorial [Link](https://www.youtube.com/watch?v=UNWIXYSZfZY) and for [ftp deploy](https://github.com/marketplace/actions/ftp-deploy) 

### Require
- SSH access on cpanel

### Setting
set your secret configuration in Settings > Secrets and add `New repository secret` with key
- FTP_SERVER
- FTP_USERNAME
- FTP_PASSWORD
- FTP_DIR_PROD // for production directory
- FTP_DIR_STAGING // for staging directory