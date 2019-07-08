# docker-compose-homeassistant
Docker Compose example repository based on my home server setup.
This setup contains the following:
- [portainer](https://hub.docker.com/r/portainer/portainer) => Web application for monitoring / managing Docker.
- [postgres](https://hub.docker.com/_/postgres) => Database server. Used by HomeAssistant.
- [mosquitto](https://hub.docker.com/_/eclipse-mosquitto) => MQTT server. Used by MQTT devices, zigbee2mqtt and HomeAssistant. 
- [zigbee2mqtt](https://hub.docker.com/r/koenkk/zigbee2mqtt/) => Bridge from Zigbee sniffer to MQTT.
- [homeassistant](https://hub.docker.com/r/homeassistant/armhf-homeassistant/) => Application for managing your home automation.
- [duckdns](https://hub.docker.com/r/linuxserver/duckdns) => Service for updating your DDNS record at Duck DNS.
- [letsencrypt](https://hub.docker.com/r/linuxserver/letsencrypt) => Service for creating HTTPS certificates via LetsEncrypt.
- [apache](https://hub.docker.com/_/httpd) => Web server. Used to proxy HTTP traffic to HomeAssistant.
