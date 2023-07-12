# terraria-docker-raspberrypi
Docker image for running a Terraria server on a Raspberry Pi. TShock version 1.4.4.9

## Usage
```
docker run -it -p 7777:7777 -v /home/$USER/terraria:/data --name terraria-docker fordus/terraria:latest

```

## Volumes
* `/data` - Contains the world and config files
