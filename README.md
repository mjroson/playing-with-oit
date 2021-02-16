Deploy on raspberrypi

copy and modify example.env to .env

Configure the host of broker mqtt (mosquitto) on telegraf.conf line 6803. It's the same to the raspberrypi host.

## Configure esp8266

1. open esp8266_mqtt.ino file and configure data to access your wifi network and host where located mqtt broker (raspberry host)
2. Upload esp8266_mqtt.ino code with arduino IDE on your esp8266 board.
