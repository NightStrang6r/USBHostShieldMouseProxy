<h1 align="center">
    USBHostShield Mouse Proxy
</h1>

<h4 align="center">
    This is an Arduino Leonardo sketch for proxying mouse actions to a computer using a USB Host Shield
</h4>

## ⚡ **Description**

When implementing a proxy for the mouse, I found that values from -127 to 127 are not enough to ensure that the mouse does not "lag" and does not lose speed when moving quickly.

This is a continuation of the [usb-host-shield-mouse](https://github.com/mustaffxx/usb-host-shield-mouse) project by [mustaffxx](https://github.com/mustaffxx). Its repository was taken as a basis, parsing of 16-bit values for the mouse was added, and the Mouse.h library was modified to enter 16-bit values.

This code has been tested on a Redragon mouse using an Arduino Leonardo and a USB Host Shield v2.