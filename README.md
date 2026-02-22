# esphome-reuse
all of the .yaml files I use for my esphome setup (wifi configs, sensor configs, Sonoff configs, etc.)

I use ESPHome with Home Assistant, both deployed via docker containers.

## Files Descriptions
### device-base.yaml
include base config that all devices use:
- api setup
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
- sonoff-ifan04.yaml: Sonoff smart fan controller
- sonoff-minir4.yaml: Sonoff smart switch
- sonoff-s31.yaml: Sonoff smart plug
