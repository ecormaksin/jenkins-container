# Jenkins using Docker Compose

When you use this project at first, you need to do some procedures as follows:

1. Copy `compose-ports.dist.yaml` as `compose-ports.yaml`.
2. Edit `compose-ports.yaml` for host port.
3. In the case that you use Windows, on the (Windows) Powershell terminal, run `$Env:COMPOSE_CONVERT_WINDOWS_PATHS=1`.
4. Then, on the same terminal as the previous procedure, run `docker-compose -f compose.yaml -f compose-ports.yaml up -d`.
