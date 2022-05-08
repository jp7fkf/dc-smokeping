# smokeping using docker-compose

## systemctl compose
```
cp smokeping.service /etc/systemd/system/smokeping.service
cp docker-compose.yml docker-compose.override.yml # optional
sudo systemctl daemon-reload
sudo systemctl status smokeping-service
sudo systemctl [start/stop/restart] smokeping-service
```

## References
- https://oss.oetiker.ch/smokeping/
- https://hub.docker.com/r/linuxserver/smokeping
- https://oss.oetiker.ch/rrdtool/
