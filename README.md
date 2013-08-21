smartapp.off-without-motion
===========================

This app is designed to be a "smarter" version of the *Darken Behind Me* app.

The original *Darken Behind Me* app was designed for walking and did not
adapt well to sitting in a room.  As the motion detection was is not all
that finely grained, sitting in a room reading a book (for example) may
not trigger the motion.

So, this version allows for a configurable grace period before turning off
the lights so that the motion detection can have a chance to catch you
moving.

If the device catches you moving within the grace period, much like your
computer screen-saver app, it will restart the countdown clock.

## Installation

1. Browse to My SmartApps (https://graph.api.smartthings.com/ide/apps)
1. Create a [New SmartApp] with the following details
    * Author: http://github.com/smartthings-users/smartapp.off-without-motion
    * Name: Off Without Motion
    * Description: Turn off switch(es) after there has been no motion for x minutes.
    * Icon Small: http://s3.amazonaws.com/smartapp-icons/Meta/light_motion-outlet.png
    * Icon Big: http://s3.amazonaws.com/smartapp-icons/Meta/light_motion-outlet%402x.png

1. Copy and paste the code into the IDE.
1. [Save]
1. [Publish] -> For Me
