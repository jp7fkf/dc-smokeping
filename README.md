# smokeping using docker-compose

## systemctl compose
```
cp smokeping.service /etc/systemd/system/smokeping.service
sudo systemctl daemon-reload
sudo systemctl status smokeping-service
sudo systemctl [start/stop/restart] smokeping-service
```

