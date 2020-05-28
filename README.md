## As issue now fixed in HA 0.110.0 it is not needed to use this repo

# Information
Modification of Broadlink components to support switch in Home Assistant on Raspberry Pi.

## Installation
To get started put the files from `/custom_components/broadlink_rpi/` in your folder `<config directory>/custom_components/broadlink_rpi/`

## Configuration
**Example configuration.yaml:**

```yaml
switch:
  - platform: broadlink_rpi
    host: 192.168.1.1
    mac: 'XX:XX:XX:XX:XX:XX'
    type: 'sp3'
    timeout: 15
    retry: 10
    friendly_name: 'Plug_1'
```

***
