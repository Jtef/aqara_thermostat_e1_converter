# Zigbee2MQTT Aqara Radiator Thermostat E1 custom converter

* The file `atherrade1.js` has to be created next to the `configuration.yaml` (the configuration file can be found in zigbee2mqtt folder)
* Enable the external converter by adding the following to your Zigbee2MQTT configuration.yaml.
```bash
external_converters:
  - atherrade1.js
```

Note that you probably already have external_converters: [] in your configuration. Just edit it as above.

* Restart Zigbee2mqtt addon and make sure there are no errors in the logs
* Start the pairing process as for any other zigbee device.

Enjoy!

Zigbee2mqtt custom converter documentation: https://www.zigbee2mqtt.io/advanced/support-new-devices/01_support_new_devices.html#instructions


Remove the custom converter as soon as it will be added in zigbee2mqtt.