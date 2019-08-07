# Zibee2Mqtt Assistant
This project is a _Web GUI_ for the very good [Zigbee2Mqtt system](https://www.zigbee2mqtt.io/) (Z2M).

3 ways to use it:
1. From compiled sources (here)
2. By starting a _docker container_ (not published yet)
3. By installing a _HASS-IO Add-on_ (not published yet)

## Features
* Display all joined devices, event those unsupported by Z2M
* 

## Requirements
* Simple MQTT connection with username/password (TLS supported)
  * Client certificates not supported yet
* Z2M Configuration:
  * Home Assistant Discovery **MUST** be activated - event if you're not using it.
    This shouldn't have any side effect to your installation.

    `homeassistant: true` in Z2M configuration
  * MQTT 