how to start stop nginx server in windows:

@ECHO OFF
cd /nginx
taskkill /f /IM nginx.exe
start nginx
EXIT


///////////////////
