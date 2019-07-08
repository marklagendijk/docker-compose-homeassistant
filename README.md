# docker-compose-homeassistant
Docker Compose example repository based on my home server setup.
This setup contains the following:
- portainer => Web application for monitoring / managing Docker.
- postgres => Database server. Used by HomeAssistant.
- mosquitto => MQTT server. Used by MQTT devices, zigbee2mqtt and HomeAssistant. 
- zigbee2mqtt => Bridge from Zigbee sniffer to MQTT.
- homeassistant => Application for managing your home automation.
- duckdns => Service for updating your DDNS record at Duck DNS.
- letsencrypt => Service for creating HTTPS certificates via LetsEncrypt.
- apache => Web server. Used to proxy HTTP traffic to HomeAssistant.
