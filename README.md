# esphome-reuse
all of the .yaml files I use for my esphome setup (wifi configs, MQTT configs, sensor configs, Sonoff configs, etc.)

I use ESPHome without home assistant. Everything goes through MQTT

## Files Descriptions
### device-base.yaml
include base config that all devices use:
- wifi, ota updates, and web-sever
- wifi diagnostic sensors
- mqtt
- uptime sensor
### /sensors
- aht2x.yaml
- veml7700.yaml
- sht4x.yaml
### /devices
- sonoff-s31.yaml:
- sonoff-ifan04.yaml:
