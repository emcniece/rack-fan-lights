# ESPHome Rack Fan & Lights

Controls:

- 2x 12V PWM fans with RPM feedback
- 1x FastLED strip
- 1x TMP102 I2C temperature sensor

... and exposes them to [Home Assistant](https://www.home-assistant.io/) via [ESPHome](https://esphome.io/).

Usage:

```sh
pip install esphome

esphome run rackfanleds.yaml

# Must have manual_ip set in config:
esphome logs rackfanleds.yaml
```
