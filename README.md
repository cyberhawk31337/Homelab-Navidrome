# Homelab-Music Server (Navidrome + Docker + Proxmox)
Self-hosted music server using Navidrome on Docker in a Proxmox LXC container with Tailscale remote access

> Self-hosted music streaming server with secure remote access, deployed on Proxmox VE with Docker in an LXC container.

![Status](https://img.shields.io/badge/Status-Incomplete-red)
![License](https://img.shields.io/badge/License-MIT-blue)
![Last Updated](https://img.shields.io/badge/Last%20Updated-Mar%202026-orange)

---

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




## The Setup
- 
