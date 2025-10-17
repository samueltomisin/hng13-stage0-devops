# HNG13 — DevOps Track — Stage 0

## Author
- **Name:** Samuel Gbadebo
- **Slack Username:** CloudMaestro

## Project Overview
This repository contains my Stage 0 DevOps task for HNG13.  
It demonstrates deploying an NGINX web server and serving a custom webpage over HTTP on port 80.

## Live Deployment
- **Server URL:** http://YOUR_SERVER_IP/
- **Platform:** AWS
- **Deployed On:** YYYY-MM-DD

## What’s Included
- Customized `index.html` at `/var/www/html/index.html` rendered by NGINX.
- Documentation of steps to provision, secure, and validate the deployment.

## Quick Start (What I Ran)
```bash
# Connect
ssh ubuntu@YOUR_SERVER_IP

# Install NGINX
sudo apt update && sudo apt install -y nginx
sudo systemctl enable --now nginx

# Allow HTTP (if ufw is enabled)
sudo ufw allow 80/tcp

