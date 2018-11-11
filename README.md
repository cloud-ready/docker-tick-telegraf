# docker-tick-telegraf
Telegraf - Component of the TICK Stack

see: https://hub.docker.com/_/telegraf/

see: https://github.com/influxdata/TICK-docker


Get default Telegraf config
```bash
docker run --rm telegraf:${IMAGE_TAG:-1.8.3} telegraf config > telegraf.conf
```
