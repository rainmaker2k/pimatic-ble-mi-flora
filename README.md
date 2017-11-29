pimatic-mi-flora
=================

Pimatic Plugin that monitors Xiaomi Mi Flora ble devices

Configuration
-------------
If you don't have the pimatic-ble plugin add it to the plugin section:

    {
      "plugin": "ble"
    }

Then add the plugin to the plugin section:

    {
      "plugin": "mi-flora"
    },

Then add the device entry for your device into the devices section:

    {
      "id": "mi-flora",
      "class": "MiFloraDevice",
      "name": "Plant",
      "uuid": "c47c8d000000",
      "interval": 60000
    }

Then you can add the items into the mobile frontend