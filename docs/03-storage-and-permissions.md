# Storage & Permissions

## Objective
Organize storage and enforce appropriate access.

## Tasks
- Identify disks/filesystems
- Define media/data directories
- Create service users/groups where appropriate
- Set ownership and permissions
- Configure file sharing only if needed
- Test authorized and unauthorized access with lab accounts

## Validation
```bash
lsblk
df -h
ls -la
id
```

## Evidence
Capture storage layout and permissions without exposing private files.
