# Unblock Youtube For 1 Hour

This is an AppleScript application that will help you limit the time you spend watching YouTube. This is done by removing comments for specific lines in the /etc/hosts file.

## It uses 3 files:
- ### unblockYT 
    *bash script to uncomment the YT lines*
- ### blockYT 
    *bash script to comment the YT lines*
- ### Unblock Youtube For 1 Hour.app
    *A Mac application that will automatically run the bash scripts<br/> and close all YouTube tabs in Firefox after 1 hour has passed*

<br/>

# To set up

### 1. Paste the contains of `insert.txt` at the end of your `/etc/hosts` file
### 2. Put `unblockYT` and `blockYT` into `~/Scripts`
### 3. Run `Unblock Youtube For 1 Hour.app`, enter the administrator password
### 4. Watch YouTube! (it will be blocked automatically in 1 hour)