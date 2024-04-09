# NGINX Proxy Manager
I use NGINX Proxy Manager to give all my local servers subdomains and HTTPS easily so I don't have to remember IPs and ports and to ensure compatibility.

## Modifications Made
This is just the [normal docker compose file](https://nginxproxymanager.com/setup/#running-the-app) but also with the [healthcheck](https://nginxproxymanager.com/advanced-config/#docker-healthcheck) to make sure the container is running optimally.
