# smokeping using docker compose

## systemctl compose
```
vim dc-smokeping.service # optional (ex. path to workingdir)
sudo ln -s /home/composer/dc-smokeping.service /etc/systemd/system/
cp docker-compose.yml docker-compose.override.yml # optional
sudo systemctl daemon-reload
sudo systemctl status dc-smokeping.service
sudo systemctl [start/stop/restart] dc-smokeping.service
```

## References
- https://oss.oetiker.ch/smokeping/
- https://hub.docker.com/r/linuxserver/smokeping
- https://oss.oetiker.ch/rrdtool/
