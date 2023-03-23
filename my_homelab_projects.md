# My Homelab Project Ideas
See MikeRoyal's [Master HomeLab Guide](https://github.com/mikeroyal/Self-Hosting-Guide) for reference and homelab ideas!

- [x] [Set up secure tunnel via CloudFlare's DNS](https://www.youtube.com/watch?v=ey4u7OUAF3c)
- [x] [Expose homelab to the internet](https://www.youtube.com/watch?v=ey4u7OUAF3c)
- [ ] Create HA Kubernetes cluster via Ansible playbook; [see Techno Tim's doc](https://docs.technotim.live/posts/k3s-etcd-ansible/)
- [ ] [Install Rancher on top of Kubernetes cluster](https://ranchermanager.docs.rancher.com/v2.5/pages-for-subheaders/install-upgrade-on-a-kubernetes-cluster)
- [ ] Build Docker containers via Rancher w/K3S to run all the following web apps:
  - [ ] Secure network access via [TailScale](https://tailscale.com/kb/1039/install-ubuntu-2004/)
  - [ ] Reverse Proxy via [Kemp Loadmaster](https://github.com/bmurrtech/my-road-to-tech-job-in-22-days#kemp-loadmaster)
  - [ ] VNC Remote Access to Homelab apps via [Guacamole}(https://www.youtube.com/watch?v=gsvS2M5knOw)
  - [ ] Setup [Cloudron](https://www.cloudron.io/store/index.html) free account
    - [ ] Add subdomain DNS A records to Cloudflare
    - [ ] Install Apache Guacamole
  - [ ] [Cybersecurity](https://github.com/bmurrtech/0-100-days-cloud-engineer/blob/main/home_network_cybersecurity.md) steps to secure homelab.
    - [ ] SSO Authelia Setup
  - [ ] Pterodactyl + Docker [game server](https://docs.technotim.live/posts/pterodactyl-game-server/)
  - [ ] Homer (interface for NAS)
  - [ ] [ownCloud](https://owncloud.com/pricing/) - self-hosted cloud with mobile apps; [see support docs](https://owncloud.com/docs-guides/)
  - [ ] [MongoDB Database](https://www.mongodb.com/pricing) 512MB "Shared" free version - for building user database (i.e. Ant Media Server, Wordpress users, etc.)
  - [ ] Jellyfin media server (install on Synology NAS)
  - [ ] Openbooks (ebooks media server)
  - [ ] Deluge (BitTorrent client written in Python)
  - [ ] Jakcett (torrent tracker) + Sonarr & Radarr
  - [ ] PhotoPrism - The iPhone Photo Killer (set up automation in WebDav to auto-upload)
  - [ ] BitWarden | run [VaultWarden - open-source compatible server](https://github.com/dani-garcia/vaultwarden)
  - [ ] PiHole (VPN into home network, local DNS server, recursive DNS resolver, run Unbound)
  - [ ] pfSense (VLANs, cybersecurity, port-forwarding)
  - [ ] HomeAssistant (for home automation)
  - [ ] [Paperless-ngx](https://docs.paperless-ngx.com/) - open-sorce document managment system that transforms physical documents into a searchable online archive. Can install via Cloudron.
- [ ] Pi-KVM (video-capture of home server: HDMI capture card + Raspberry Pi)

# Cloud Provider Projects
- [ ] [Deploy WordPress website in AWS](https://www.aosnote.com/offers/xFzqby9z/checkout) (use `TECHWITHLUCY` promo code at check out for 20% off)
  - [ ] Add "AWS Project. Deployed and hosted a highly-available WordPress app using EC2, RDS, Route 53, ASG, and VPC." to resume
- [ ] [Serverless Web Application on AWS](https://aws.amazon.com/getting-started/hands-on/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/)
- [ ] [Chat Bot Amazon Connect Call Center on AWS](https://github.com/aws-samples/amazon-lex-connect-workshop)
