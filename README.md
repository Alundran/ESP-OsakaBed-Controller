# Dreams Osaka TV Bed ESP Controller
If you have an ESP device such as the M5 Stack Atom, you can use this ESP config to control the raising & lowering of the TV motor. It works by using BLE (Bluetooth Low Energy), sending the required values for raising & lowering. With integration to Home Assistant, you can add automations such as auto raising the TV when the TV is turned on and lowering when turned off.

# Using this config
You'll need to amend the redacted values in the config such as the encryption key with your own key to allow communication with Home Assistant. You'll also need to amend the ```mac_address``` in the yaml config with the bluetooth mac address of your own Osaka TV Bed.
