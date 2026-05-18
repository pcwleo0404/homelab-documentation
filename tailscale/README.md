# Tailscale Remote Access Setup

## Goal

Secure remote access to my homelab and local network without traditional port forwarding.

---

# Why I Use Tailscale

I wanted a simple and secure way to:
- access my homelab remotely
- manage devices from outside my home network
- securely connect to internal services
- avoid exposing ports directly to the internet

Tailscale solves this by creating a private mesh VPN using WireGuard.

---

# Current Setup

## Devices Connected

| Device | Purpose |
|---|---|
| Raspberry Pi Zero 2W | Pi-hole + network access |
| Windows PC | Main workstation |
| MacBook | Mobile administration |
| Smartphone | Remote monitoring |

---

# Features

- Remote SSH access
- Access to local web interfaces
- Secure encrypted VPN tunnel
- Easy device management
- Works behind NAT

---

# Planned Features

- Subnet routing
- Exit node
- Homelab monitoring
- Remote Docker management
- Internal DNS improvements

---

# Learning Goals

- VPN fundamentals
- WireGuard basics
- Remote infrastructure management
- Secure networking
- Linux networking

---

# Notes

This project is part of my personal homelab and cybersecurity learning journey.
