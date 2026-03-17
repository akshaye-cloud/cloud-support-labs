# Project: Local Web Server Setup using nginx

## Objective

Install nginx and run a local web server.

---

## Step 1: Update system packages

Command: 
sudo apt update

---

## Step 2: Install nginx

Command:
sudo apt install nginx


Verify installation:
nginx -v

---

## Step 3: Start nginx service

Command:
sudo systemctl start nginx

Check service status:
sudo systemctl status nginx


Expected output:
Active: active (running)

---

## Step 4: Access the web server

Open browser:
http://localhost
or
http://127.0.0.1

Result:
nginx welcome page appears.

---

## Step 5: Check open ports

Command:
sudo ss -tulnp

Expected:
Port 80 listening.

---

## Step 6: Stop nginx

sudo systemctl stop nginx

---

## Step 7: Restart nginx

sudo systemctl restart nginx

---

## Outcome

Successfully installed nginx and ran a local web server.
This demonstrates basic server setup similar to deploying a web server in cloud environments.
