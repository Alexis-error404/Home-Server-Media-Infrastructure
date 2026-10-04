# Home Server & Media Infrastructure

**Linux • Docker • Storage • Media • Operations**

## Project Summary
Build a maintainable Linux home server that combines storage, containerized services, media infrastructure, permissions, monitoring, backup, and recovery.

This repository is structured as a portfolio project: architecture, implementation, validation, security considerations, troubleshooting, and screenshot evidence are documented so the work can be reproduced and discussed in a technical interview.

## Architecture
```text
Home Network
     |
 Linux Server
     |
 +---+---------+---------+
 |             |         |
Storage      Docker    Monitoring
 |             |
Shares     Media Service
               |
          Client Devices
```

## Core Skills
- Linux
- Docker
- Storage
- File Permissions
- SMB/NFS Concepts
- Media Services
- Monitoring
- Backup
- Systemd

## Project Documentation
1. [Server Design](docs/01-server-design.md)
2. [Linux Installation](docs/02-linux-installation.md)
3. [Storage And Permissions](docs/03-storage-and-permissions.md)
4. [Docker Services](docs/04-docker-services.md)
5. [Media Service](docs/05-media-service.md)
6. [Monitoring And Backups](docs/06-monitoring-and-backups.md)
7. [Maintenance And Troubleshooting](docs/07-maintenance-and-troubleshooting.md)
8. [Screenshot Evidence](images/README.md)

## Validation Standard
For every major component I document:
1. **Purpose** — why the component exists.
2. **Configuration** — how I deployed it.
3. **Validation** — commands/tests proving it works.
4. **Troubleshooting** — likely failure points and diagnostic steps.
5. **Security** — how access and exposure are reduced.
6. **Evidence** — sanitized screenshots of the completed work.

## Portfolio Safety
No real passwords, secrets, API tokens, private keys, product keys, recovery codes, personal data, or sensitive public-facing configuration should be committed.

## What This Project Demonstrates
Rather than only listing technologies on a résumé, this lab provides evidence of planning, implementation, administration, documentation, troubleshooting, and security-minded decision making.

## Author
**Alexis Wiscovitch** — [@Alexis-error404](https://github.com/Alexis-error404)
