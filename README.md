# xscreensaver-displayhelper
Disable Raspberry Pi Official 7" Touchscreen or HDMI after xscreensaver starts
===============================================================================

DESCRIPTIONS
------------
normaly are screen blank not same display physical off. This Tool let hdmi or touchscreen after timeout go power off.

DEPENDENCY
----------
install tvservice and xscreensaver

INSTALL
-------
Add line to autostart from LXDE (~/.config/lxsession/LXDE-pi/autostart) if you want your touchscreen after 5 seconds off:

`~/bin/xscreensaver-displayhelper 5 touch&`

SYNOPSIS
--------
Display off after # Seconds

`xscreensaver-displayhelper [delay in s]`

Display Off after # Seconds only Touchscreen or HDMI

`xscreensaver-displayhelper [delay in s] [touch|hdmi]`

status of display (on|off)

`xscreensaver-displayhelper  -s, --status  "`

Touchscreen/Hdmi off

`xscreensaver-displayhelper  -f, --off`

Touchsceen/Hdmi on

`xscreensaver-displayhelper  -o, --on`

Help Text

`xscreensaver-displayhelper  -h, --help    `

SOURCE
------
Based on https://github.com/ramses0/xscreensaver-pi-hdmi/ and https://www.raspberrypi.org/forums/viewtopic.php?t=56944&p=429723
I add Support for 7" Touchscreen and few flags

