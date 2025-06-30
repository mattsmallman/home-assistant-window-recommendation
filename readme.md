# Home Assistant Window Action Recommendation Blueprint

This blueprint recommends whether to open, close, or do nothing with a window based on indoor and outdoor temperatures, with a comfort threshold to prevent opening windows in cold weather.

## Features
- Supports individual windows (create multiple automation instances)
- Configurable comfort temperature threshold
- Sends push notifications when action is recommended

## Blueprint Path
`blueprints/automation/mattsmallman/window_recommendation.yaml`

## Import This Blueprint
[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Fmattsmallman%2Fhome-assistant-window-recommendation%2Frefs%2Fheads%2Fmain%2Fhome-assistant-window-recommendation%2Fblueprints%2Fautomation%2Fmattsmallman%2Fwindow-recommendation.yaml)

## Example Usage
- Room temperature sensor: `sensor.bedroom_temperature`
- Outside temperature sensor: `sensor.outside_temperature`
- Window sensor: `binary_sensor.bedroom_window`
- Comfort threshold: 15°C

## Setup
- Create one automation per window.
- Adjust the comfort threshold per window/room.

## License
MIT License
