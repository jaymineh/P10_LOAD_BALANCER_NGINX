# Project 10 - Load Balancer Solution With NGINX & SSL/TLS

**Step 1 - Configure NGINX As A Load Balancer**
---

- Spin up a new Ubuntu server for the NGINX load balancer. Open up ports 80 and 443 for HTTP & HTTPS traffic.

- Update and upgrade the server.

- Update the `/etc/hosts` file for local DNS with Web Servers’ names (e.g. Web1 and Web2) and their local IP addresses.

- Install nginx by running `sudo apt install nginx`.

**Step 2 - Configure Local DNS On NGINX**
---

- Run `sudo vi /etc/nginx/nginx.conf` to open the nginx config file to configure the LB using the web server names defined in `/etc/hosts`.

- Save the config file and restart nginx. After restarting, check the status of nginx to confirm it is working.

**Step 3 - Register A New Domain Name And Configure Secured Connection Using SSL/TLS Certificates**
---

- 