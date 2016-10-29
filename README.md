Make a script that will assure apache server is running and site is accesible.
If apache has an error, take action to restore service and sent an alert to an email address.  
Script will need to check for : proccess is running, apache is listening on 80 port, url status is 200, page contains a word (you choose).
Only if all checks are ok apache can be considered to be live.
If service is still down after 5 checks, script needs to escalate the issue to an alternate email address.
info:
script will need to check apache every 2 minutes. only between 8:00AM - 5:00PM.
