# DeceasedCraft Server

Documentation for image being used: [docker image](https://docker-minecraft-server.readthedocs.io/en/latest/)

## Useful Commands

### Start Server

```pwsh
docker compose up -d
```

*This will apply any config changes*

### Check Status

```pwsh
docker compose ps
```

### Check Logs

```pwsh
docker compose logs -f
```

### Join RCON

```pwsh
docker exec -i deceased-craft-server rcon-cli
```

or

```pwsh
docker attach deceased-craft-server
```

*Use Ctrl+p Ctrl+q to quit when attached!*

### Stop Server

```pwsh
docker compose stop
```
