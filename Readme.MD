# About
Bash Script to Fetch Logs from HTTP log file from the http server.

The logs will be fetched as follows:-

-----------------------
IP: x.x.x.x
---------------------------
TIMESTAMP: 14/Mar/2022:23:17:10
HTTP METHOD: GET
Endpoint: /
HTTP_STATUS: 200
USER_AGENT: "curl/7.68.0"
----------------------------------

# Command Syntax:- 
 #bash logscript.sh -f <logfile> -remoteip <x.x.x.x>

-f          --  log file
-remoteip   -- IP of user who has accessed

eg:- # bash log_script.sh -f access.log -remoteip 192.168.29.20