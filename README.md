# ha-blueprints
Home Assistant Blueprints

## Automations

### Shelly Remote

Allows you to easily define actions per channel for the [Shelly BLU Remote Control ZB](https://www.shelly.com/products/shelly-blu-remote-control-zb-white)

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2FPatrick762%2Fha-blueprints%2Frefs%2Fheads%2Fmain%2Fautomation%2Fshelly_remote.yaml)

### Dual Motion Sensor Light

Allows you to toggle a light based on two motion sensors. Prevents the light to turn off if one sensor has no more motion detected.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FPatrick762%2Fha-blueprints%2Fraw%2Frefs%2Fheads%2Fmain%2Fautomation%2Fdual_motion_light.yaml)

### Thermostat Window Sensor

Turns off the thermostat if window is open

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FPatrick762%2Fha-blueprints%2Fraw%2Frefs%2Fheads%2Fmain%2Fautomation%2Fwindow_thermostat.yaml)

### Motion Alert Light

Set a light to different color per motion alert

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FPatrick762%2Fha-blueprints%2Fraw%2Frefs%2Fheads%2Fmain%2Fautomation%2Fmotion_alert.yaml)

## Scripts

### Play Media

Plays media on a media player with specified volume

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FPatrick762%2Fha-blueprints%2Fraw%2Frefs%2Fheads%2Fmain%2Fscript%2Fplay_media.yaml)

## Combinations

### Media Player Timer

Allows you to play media for a specific duration and stops it after the timer expired. Requires a timer entity

Script:

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FPatrick762%2Fha-blueprints%2Fraw%2Frefs%2Fheads%2Fmain%2Fscript%2Fplay_media_timed.yaml)

Automation (tracks the timer):

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FPatrick762%2Fha-blueprints%2Fraw%2Frefs%2Fheads%2Fmain%2Fautomation%2Fmedia_stop_after_timer.yaml)
