# Linux Cheat Sheet

## System Information

```bash
uname -a
hostnamectl
uptime
free -h
df -h
```

---

# Network Commands

```bash
ip a
ping 8.8.8.8
ss -tulpen
netstat -tulpen
```

---

# SSH

## Connect via SSH

```bash
ssh user@ip-address
```

## Generate SSH Key

```bash
ssh-keygen
```

---

# File Management

```bash
ls
cd
pwd
cp
mv
rm
mkdir
touch
```

---

# Permissions

## Change Permissions

```bash
chmod 755 file
```

## Change Owner

```bash
chown user:user file
```

---

# Services

## Service Status

```bash
systemctl status service
```

## Restart Service

```bash
systemctl restart service
```

## Logs

```bash
journalctl -xe
```

---

# Docker

## Show Containers

```bash
docker ps
```

## Show All Containers

```bash
docker ps -a
```

## Start Compose Stack

```bash
docker compose up -d
```

## Stop Compose Stack

```bash
docker compose down
```

---

# Monitoring

## CPU / RAM Usage

```bash
htop
```

## Disk Usage

```bash
du -sh *
```

---

# Notes

This cheat sheet is part of my Linux and homelab learning journey.
