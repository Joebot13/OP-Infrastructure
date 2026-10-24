
## 10-23-26: locked down argon, AdGuard is live

- SSH keys only, DHCP reservation (.10), tmux, ufw, auto security updates
- 500G LVM volume at /srv/data, Docker data lives there
- AdGuard Home in Docker, router hands out argon as DNS (1.1.1.1 as backup)

Learned:
- "refused" = host is up, nothing listening. "timed out" = asleep or wrong IP
- Docker bypasses ufw, so AdGuard runs on host networking
- Test firewall rules from a different machine, not the host itself

Next: Tailscale, UPS monitoring (NUT), VLANs on the SG2008
