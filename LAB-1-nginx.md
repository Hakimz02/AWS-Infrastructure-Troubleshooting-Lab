
 What I did
Stopped Nginx service.

Result
Website stopped working.

Diagnosis
Checked service status using systemctl.

Fix
Restarted Nginx service.

Commands
sudo systemctl stop nginx
sudo systemctl status nginx
sudo systemctl start nginx

if not use sudo cant start and stop nginx 
