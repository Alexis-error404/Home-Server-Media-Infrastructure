# Docker Services

## Objective
Run home-server applications in manageable containers.

## Tasks
- Install Docker/Compose
- Create a project directory
- Use persistent volumes
- Define only required ports
- Configure restart behavior
- Start containers
- Inspect logs and health

## Validation
```bash
docker compose ps
docker ps
docker compose logs --tail=100
```

Never commit secrets embedded in Compose/environment files.
