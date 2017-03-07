# Microsoft high dpi scroll wheel fix for Linux

This is a fix for the sensitivity issues of some sepcific microsoft mice that have high dpi scroll wheel.
When dual booting windows and Linux, windows configures the mouse in a way that causes the scrolling in Linux to be unusable.

# Supported devices

  - Microsoft scuplt ergonomic - productId = 0x7a5
  - feel free to add support for more microsoft mice :)

# Explenation of the fix
the fix turns off the feature of high resolution scrolling of the mouse.
this is the feature with the hid-feature-id of 0x12.
