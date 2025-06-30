# Home Assistant Window Action Recommendation Blueprint

This blueprint recommends whether to open, close, or do nothing with a window based on indoor and outdoor temperatures, with a comfort threshold to prevent opening windows in cold weather.

## Features
- Supports individual windows (create multiple automation instances)
- Configurable comfort temperature threshold
- Sends push notifications when action is recommended

## Blueprint Path
`blueprints/automation/mattsmallman/window_recommendation.yaml`

## Import This Blueprint
[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?repository_url=https://github.com/mattsmallman/home-assistant-window-recommendation&file=blueprints/automation/your_github_username/window_recommendation.yaml)

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
