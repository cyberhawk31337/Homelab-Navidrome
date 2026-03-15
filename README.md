# Homelab-Navidrome
Self-hosted music server using Navidrome on Docker in a Proxmox LXC container with Tailscale remote access

## Overview
This project deploys a self-hosted music streaming server using Navidrome inside a Docker container running in an LXC container on Proxmox.

## Technologies
- Proxmox VE
- Docker
- Navidrome
- Tailscale
- Samba

## Architecture
Phone → Tailscale → Proxmox Host → LXC Container → Docker → Navidrome
| Personal PC → Samba → Proxmox Host → Navidrome

## Features
- Self-hosted music streaming
- Secure remote access
- Containerized deployment
