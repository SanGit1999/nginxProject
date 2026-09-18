# AWS EC2 Nginx DevOps Project
 
## Project Overview
 
Configured an Ubuntu EC2 instance and installed Nginx.
 
## Tasks Completed
 
- Created Ubuntu EC2 instance
- Connected using SSH / EC2 Instance Connect
- Installed Nginx
- Configured Nginx
- Created custom HTML page
- Verified Nginx service
- Checked access and error logs
- Created Nginx monitoring shell script
- Stored configuration in Git
- Pushed project to GitHub
 
## Useful Commands
 
```bash
sudo systemctl status nginx
sudo nginx -t
sudo systemctl restart nginx
sudo tail -f /var/log/nginx/access.log
sudo tail -20 /var/log/nginx/error.log


