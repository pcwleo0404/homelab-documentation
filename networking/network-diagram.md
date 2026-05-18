# Homelab Network Diagram

```text
                 Internet
                     │
              ┌────────────┐
              │  FritzBox  │
              └─────┬──────┘
                    │
     ┌──────────────┼──────────────┐
     │              │              │
┌──────────┐   ┌──────────┐   ┌──────────┐
│ Pi Zero  │   │ Windows  │   │ MacBook  │
│ Pi-hole  │   │ Main PC  │   │ Admin    │
│Tailscale │   │Tailscale │   │Tailscale │
└──────────┘   └──────────┘   └──────────┘

```

---

# Components

| Device | Purpose |
|---|---|
| FritzBox | Main router |
| Raspberry Pi Zero 2W | Pi-hole DNS server |
| Windows PC | Main workstation |
| MacBook | Administration |
| Tailscale | Secure remote access |

---

# Planned Expansion

- Docker host
- Monitoring server
- VLAN separation
- ESP32 devices
- NAS integration
- Reverse proxy
