# Home Assistant Blueprints

## Climate ventilation advisory

This blueprint advises when to open or close windows and doors to use outdoor air for indoor temperature regulation.

### Features

- Advises when to open windows for cooling
- Advises when to close windows again
- Uses indoor and outdoor temperature
- Checks weather and wind
- Checks whether selected windows/doors are already open
- Supports Danish, English and German advisory text
- Optional notification
- Optional TTS to media players

### Requirements

- Indoor temperature sensor
- Outdoor temperature sensor
- Weather entity
- Window/door contact sensors
- Person entities
- Optional notify target
- Optional TTS entity and media player

### Import

Use this URL in Home Assistant:

```[text]
https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2FHoekeren%2Fhome-assistant-blueprints%2Frefs%2Fheads%2Fmain%2Fautomation%2Fclimate_ventilation_advisory.yamlINDSÆT_DIN_RAW_URL_HER
