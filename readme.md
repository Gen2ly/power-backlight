### Description

Set screen backlight brightness dependent on power source type.  A udev rule detects power source type and runs `power-backlight [power option]`.  __power-backlight__ requires graphic driver support for ACPI in `/sys/class/backlight` to be able to work.

### Usage

Edit `/etc/default/power-backlight.conf` to set backlight level.  When first power source change occurs, backlight level will change if graphic driver support is available.
