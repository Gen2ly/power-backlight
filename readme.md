### Description

Set screen backlight brightness dependent on power source type; with udev rule backlight is adjusted on change of power source.  Requires graphic driver support for ACPI in `ic|/sys/class/backlight`.

### Usage

When first power source change occurs it will be evident if it works.  Edit `/etc/default/power-backlight.conf` to change values.
