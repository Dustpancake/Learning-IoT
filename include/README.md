### Create `secrets.h` here
The format is
```c
#ifndef SECRETS_H
#define SECRETS_H 

#define SSID_NAME "SSID_OF_YOUR_WIFI"
#define WPA_PASSWORD "WIFI_PASSWORD"

#define MQTT_SERVER_ADDR "SERVER_ADDRESS"
#define MQTT_TOPIC "TOPIC_NAME"

#define LOG_LEVEL 6	// set to 0 for production
#define DHTPIN 7

#define CYCLE_DELAY_MILLIS 60000 // one minute
#define MEAS_THRESHOLD 0.2

#endif
```
