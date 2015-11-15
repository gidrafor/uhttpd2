uHTTPd
======

uHTTPd is a web server written from scratch by OpenWrt/LuCI developers. It is aimed towards being an efficient and stable server, suitable for lightweight tasks commonly used with embedded devices and proper integration with OpenWrt's configuration framework (UCI). In particular, it is configured by default for the LuCI web interface to administer OpenWrt. In addition, it provides all the functionality expected of present day web servers.

Compiling uHTTPd
----------------

uHTTPd depends on the following libraries:

* liblua5.2-dev 
* libubox
* libubus
* uci

