This driver is now DEPRECATED, it hasn't been touched for years and is unlikely to build on any >= 4.x kernels!

I found that the AircrackNG driver was much better behaved and switched to it on my own systems:

git clone https://github.com/aircrack-ng/rtl8812au.git

Subsequently found this driver, much more up to date:  https://github.com/lwfinger/rtw88

Also found a note claiming that kernel 6.14 should support these devices in-tree.

rtl8811AU_rtl8821A-linux
========================

Initial repository based on Realtek driver rtl8811AU_linux_v4.3.0_10674.20140509.

Primarily intended for my Edimax EW-7811UTC AC600 USB wireless interface, but should work for any device based on the
RTL8811AU or related chips.

I needed a better-performing driver than the v4.2.2 version available for download from edimax.com, and this one
works great.

I found that similar drivers from ASUS and D-Link sources were missing the RTL8821A extensions required for my Edimax.
