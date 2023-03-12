This repository is for my personal minecraft server setup. The settings are tailored to my current setup, but they can easily be changed.

# Usage

Start the server:

```
docker compose up -d
```

Stop the server:

```
docker compose down
```

Access the minecraft server CLI:

```
docker exec -i minecraft-server-mc-1 rcon-cli
```

Manually trigger a backup:

```
docker compose exec backups backup now
```
