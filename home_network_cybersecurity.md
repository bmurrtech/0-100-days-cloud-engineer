# Home Network Cyber Security Guide & Documentation
1. Close all ports
  - use iptables/firewallD/UFW
2. Reverse proxy [how-to set up a reverse proxy in NGINX](https://kinsta.com/blog/reverse-proxy/)
 - use [swag](https://github.com/linuxserver/docker-swag)
  - Because ISP re-assigns home IP address (unless you have a static IP address as a business), it is necessary to use a dynamic DNS service to always point to your home IP when it changes
  - Get a free domain name via [DuckDNS](https://www.duckdns.org/) - Free dynamic DNS hosted on AWS VPC
  - Set up a Linux [cron job]() to update your IP address when it changes
  - But if you have your own domain name, use [DDClient](https://github.com/ddclient/ddclient)
  - If you are using CloudFlare too, use a Docker container [Docker CloudFlare DDNS](#docker-cloudflare-ddns)
3. Single-sign-on
  - so that anyone wanting to use your hosted webapps will see an authentication portal
  - use [Authelia](https://github.com/authelia/authelia)[^2fa1]
[^2fa1]: Authelia is not required for web apps that already require 2FA credentials to logon
4. use free CloudFlare plan because you don't want public to know your IP address

## Docker Cloudflare DDNS
- Refer to [the documentation](https://github.com/oznu/docker-cloudflare-ddns) for installation
- Fill out the .yml file to your specification
- Run it once
- Forget about it
