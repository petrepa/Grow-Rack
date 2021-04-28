# Grow-Rack
Built a grow rack out of a shelving unit with automation capabilities

![Finalised](https://github.com/petrepa/Grow-Rack/blob/main/Images/finalized.png)

## Why
![Before](https://github.com/petrepa/Grow-Rack/blob/main/Images/before_grow_rack.png)

## Wanted functionality
- LED Strip dimmers
    - For both shelves
    - For each channel (grow, cool white and warm white)
- Environmental sensors 
    - Temperature
    - Humidity
    - Illuminance
    - Moisture

## Build
![LED Build](https://github.com/petrepa/Grow-Rack/blob/main/Images/led_build.png)
![Wire End Piece](https://github.com/petrepa/Grow-Rack/blob/main/Images/wire_end_piece.png)
![Wire Free Mount](https://github.com/petrepa/Grow-Rack/blob/main/Images/wire_free_mount.png)

### Current setup
Currently using a spare [Shelly RGBW2](https://shelly.cloud/products/shelly-rgbw2-smart-home-automation-led-controller/) for controlling the LED strips, accompanied of a Sonoff Zigbee multi sensor.

![Home Assistant GUI](https://github.com/petrepa/Grow-Rack/blob/main/Images/shelly_grow_rack_gui.png)

| Channel | Connection                 |
|---------|----------------------------|
| 1       | Shelf 1 Grow Lights        |
| 2       | Shelf 1 Cool + Warm Lights |
| 3       | Shelf 2 Grow Lights        |
| 4       | Shelf 2 Cool + Warm Lights |

![Wiring Underside](https://github.com/petrepa/Grow-Rack/blob/main/Images/wiring_underside.png)
