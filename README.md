# esphome-reuse
all of the .yaml files I use for my ESPHome setup (wifi configs, sensor configs, Sonoff and Shelly configs, etc.)

I use ESPHome with Home Assistant, both deployed via docker containers.

## Files Descriptions

### `device-base.yaml`
include base config that all devices use:
- api setup
- ota updates
- web server
- uptime sensor
- 
### `wifi.yaml` / `ethernet.yaml`
the base config for a wifi or ethernet connected devices

### `/devices`
- `atoms3-pwm.yaml`: led strip controller
- `sonoff-ifan04.yaml`: Sonoff smart fan controller
- `sonoff-s31.yaml: Sonoff smart plug
- `sonoff-s31-lite.yaml`: Sonoff smart plug w/o power monitoring

### `/sensors`
- `aht2x.yaml`: temperature and humidity sensor
- `lps22.yaml`: pressure sensor
- `my24hcp.yaml`: Seeed Studio mmWave sensor
- `sht4x.yaml`: temperature and humdity sensor
- `veml7700.yaml`: lux sensor
