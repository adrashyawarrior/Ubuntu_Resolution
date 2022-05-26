# Ubuntu_Resolution
Fix Ubuntu Resoultion In Seconds

### ONLY_ONCE
$ xrandr
$ cvt 1368 768
### EVERY_TIME
$ sudo xrandr --newmode "1368x768_60.00"   85.25  1368 1440 1576 1784  768 771 781 798 -hsync +vsync
$ sudo xrandr --addmode VGA-1 "1368x768_60.00"
