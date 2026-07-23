---
layout: project
title: "Self-Hosting"
category: project
project_number: "0001"
start_date: 2025-04-18
last_updated: 2026-07-23
status: "Live"
scope: software
visibility: public
featured: true
tech_stack: ["Proxmox", "Linux", "Docker", "Homelab", "Networking"]
---

Running my own services at home, on my own gear.

This started after a colleague at an old company showed me his Proxmox setup and how he deployed everything with community scripts.

Big shout out to him, and to the [Proxmox VE Helper-Scripts](https://community-scripts.org/) project, where most of these services come from.

## Machine

| Spec | Detail |
|------|--------|
| Motherboard | ASUSTeK B85-PLUS |
| CPU | Intel Core i5-4670 @ 3.40GHz (4 cores / 4 threads, up to 3.8GHz) |
| RAM | 16 GB DDR3 1600 MT/s (4 x 4 GB) |

### Storage

| Disk | Size | Type |
|------|------|------|
| SATA3 SSD | 480 GB | SSD |
| TCSUNBOW X5 | 120 GB | SSD |
| WDC WD10EZEX | 1 TB | HDD |
| Maxtor STM3160211AS | 160 GB | HDD |
| Samsung HD161GJ | 160 GB | HDD |

## Services

### Network

#### In use

| Service | What it does |
|---------|--------------|
| [Nginx Proxy Manager](https://community-scripts.github.io/ProxmoxVE/scripts?id=nginxproxymanager) | Reverse proxy + SSL certificate management |
| [Pi-hole](https://community-scripts.github.io/ProxmoxVE/scripts?id=pihole) | Local DNS + network-wide ad/tracker blocking |
| [WireGuard](https://community-scripts.github.io/ProxmoxVE/scripts?id=wireguard) | VPN into the home network |

#### Trying

| Service | What it does |
|---------|--------------|
| [HAOS 16.2](https://community-scripts.github.io/ProxmoxVE/scripts?id=haos-vm) | Home Assistant OS |
| [PiAlert](https://community-scripts.github.io/ProxmoxVE/scripts?id=pialert) | Network device monitoring & alerts |

### Personal apps

#### In use

| Service | What it does |
|---------|--------------|
| [Audiobookshelf](https://community-scripts.github.io/ProxmoxVE/scripts?id=audiobookshelf) | Audiobooks & podcasts |
| [Dashy](https://community-scripts.github.io/ProxmoxVE/scripts?id=dashy) | Single dashboard for everything |
| [Jellyfin](https://community-scripts.github.io/ProxmoxVE/scripts?id=jellyfin) + *arr stack | Movies & TV streaming with automated libraries |
| [LubeLogger](https://community-scripts.github.io/ProxmoxVE/scripts?id=lubelogger) | Vehicle maintenance & fuel logging |
| [Navidrome](https://community-scripts.github.io/ProxmoxVE/scripts?id=navidrome) | Music streaming |
| [Syncthing](https://community-scripts.github.io/ProxmoxVE/scripts?id=syncthing) | File sync across devices |
| [Vaultwarden](https://community-scripts.github.io/ProxmoxVE/scripts?id=vaultwarden) | Password manager |

#### Trying

| Service | What it does |
|---------|--------------|
| [Adventure Log](https://community-scripts.github.io/ProxmoxVE/scripts?id=adventurelog) | Travel & adventure logging |
| [ezBookkeeping](https://community-scripts.github.io/ProxmoxVE/scripts?id=ezbookkeeping) | Personal finance & bookkeeping |
| [Immich](https://community-scripts.github.io/ProxmoxVE/scripts?id=immich) | Photo & video management |
| [Wanderer](https://community-scripts.github.io/ProxmoxVE/scripts?id=wanderer) | Hiking & trail maps |
| [Wealthfolio](https://community-scripts.github.io/ProxmoxVE/scripts?id=wealthfolio) | Investment portfolio tracking |

### Production apps

Apps running for [RCELO-SOFTWARE](/projects/0002-rcelo-software/).

#### In use

| Service | What it does |
|---------|--------------|
| [Odoo](https://community-scripts.github.io/ProxmoxVE/scripts?id=odoo) | ERP for RCELO-SOFTWARE |

#### Trying

| Service | What it does |
|---------|--------------|
| [Jenkins](https://community-scripts.github.io/ProxmoxVE/scripts?id=jenkins) | CI/CD for RCELO-SOFTWARE |
| [n8n](https://community-scripts.github.io/ProxmoxVE/scripts?id=n8n) | Workflow automation for RCELO-SOFTWARE |
| [RabbitMQ](https://community-scripts.github.io/ProxmoxVE/scripts?id=rabbitmq) | Message broker for RCELO-SOFTWARE |

---

## Update #1 (2026-07-23)

- Documented the current stack and the services actually in use.
