# Uptime Kuma

Uptime Kuma provides simple availability monitoring for homelab and home-network services.

## Address

http://orbital.local:3001

## Runtime data

Persistent data is stored at:

`/srv/containers/uptime-kuma`

This directory is not tracked by Git.

## Service management

```bash
systemctl --user status uptime-kuma
systemctl --user restart uptime-kuma
journalctl --user -u uptime-kuma
