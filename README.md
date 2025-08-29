# esphome-reuse
all of the .yaml files I use for my esphome setup (wifi configs, MQTT configs, sensor configs, Sonoff configs, etc.)

I use ESPHome without home assistant. Everything goes through MQTT

## Files Descriptions
### device-base.yaml
include base config that all devices use:
- mqtt
- ota updates
- web server
- uptime sensor
### wifi.yaml and ethernet.yaml
the base config for a wifi or ethernet connected devices
### /sensors
- aht2x.yaml: temperature and humidity sensor
- lps22.yaml: pressure sensor
- my24hcp.yaml: Seeed Studio mmWave sensor
- sht4x.yaml: temperature and humdity sensor
- veml7700.yaml: lux sensor
### /devices
- sonoff-ifan04.yaml
- sonoff-minir4.yaml:
- sonoff-s31.yaml: