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
Add in you autostart from LXDE (~/.config/lxsession/LXDE-pi/autostart) following line if you want your touchscreen after 5 seconds off:

`~/bin/xscreensaver-displayhelper 5 touch&`

SYNOPSIS
--------

`xscreensaver-displayhelper [delay in s]`

`xscreensaver-displayhelper  -s, --status  status of display (on|off)"`

`xscreensaver-displayhelper  -f, --off     Touchscreen/Hdmi off`

`xscreensaver-displayhelper  -o, --on      Touchsceen/Hdmi on`

`xscreensaver-displayhelper  -h, --help    This help text`

