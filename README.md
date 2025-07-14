## 😸 Hi, I'm Elliot!

### 🥱 TL;DR

DS Stdnt + NSF SINDy Rsrch Asst + Intrn @ MedPro + Cmptr Nrd

### 🗣️ More Details

- Studying B.S. Data Science & Applied Statistics (minors: Actuarial Science, CS, Mathematics) at Purdue University Fort Wayne
- Researching dynamical systems & sparse identification (SINDy) for an NSF-funded methods project
- Analyzing messy data and developing data stories for full-funnel marketing data at MedPro Group

### 😁 Recent Personal Projects

#### PiHole DNS Server on a ThinkPad Yoga 11e (DietPi Linux)

An underpowered school laptop converted into a network-wide ad-blocking, privacy-focused DNS server. It runs Pi-hole (FTL/dnsmasq) for blacklist-based DNS filtering and Unbound for true recursive DNS resolution. DietPi is a super lightweight Debian OS typically used on Raspberry Pi-type computers, but fit well for my DNS server use case.

#### Home-Lab on a 2010 Mac Pro (Linux Mint)

A classic 2010 Mac Pro saved from the scrapyard and repurposed as a Linux Mint server. It hosts a secure, containerized web-and-media platform using Docker with automatic HTTPS, SSO, media organization and backups, LAN file sharing, and self-updating services, all behind a hardened reverse-proxy + auth layer.

| Layer                  | Applications                                     | Purpose                                           |
|------------------------|--------------------------------------------------|---------------------------------------------------|
| **Container Platform** | **Docker**                                       | Reproducible deployments via Docker Compose       |
| **Website**            | **NGINX** + **Certbot**                          | Reverse proxy & automatic TLS                     |
| **Auth**               | **Authelia**                                     | SSO with 2FA                                      |
| **Media**              | **Sonarr**, **Radarr**, **Bazarr**, **Prowlarr** | Library automation & metadata                     |
| **File Sharing**       | **Samba**                                        | LAN-only file share for curated media             |
| **Cloud Backups**      | **BackBlaze + Rclone**                           | Daily syncs with built-in recently deleted bucket |
| **Maintenance**        | **Watchtower**, **Redis**                        | Zero-downtime auto-updates & caching              |
