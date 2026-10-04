# Maintenance & Troubleshooting

Patch Linux, update container images deliberately, check disk space, review logs, verify backups, and document changes.

```bash
df -h
free -h
systemctl --failed
journalctl -p err
docker compose ps
docker compose logs --tail=100
ss -tulpn
```

Troubleshoot: hardware/storage -> OS -> network -> Docker -> service -> client. Document one real issue from symptom through validated resolution.