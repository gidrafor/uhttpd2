uHTTPd
======

uHTTPd is a web server written from scratch by OpenWrt/LuCI developers. It is aimed towards being an efficient and stable server, suitable for lightweight tasks commonly used with embedded devices and proper integration with OpenWrt's configuration framework (UCI). In particular, it is configured by default for the LuCI web interface to administer OpenWrt. In addition, it provides all the functionality expected of present day web servers.

Compiling uHTTPd
----------------

On Ubuntu 14.04 LTS, uHTTPd requires:

* libjson0-dev
* libjson-c-dev
* lua5.1 
* liblua5.1-dev 
    sudo ln -s /usr/include/lua5.1/lua.h /usr/include/lua.h
    sudo ln -s /usr/include/lua5.1/luaxlib.h /usr/include/luaxlib.h
    sudo ln -s /usr/include/lua5.1/luaconf.h /usr/include/luaconf.h
    sudo ln -s /usr/include/lua5.1/lua.hpp /usr/include/lua.hpp
    sudo ln -s /usr/include/lua5.1/lualib.h /usr/include/lualib.h
* libubox - git://nbd.name/luci2/libubox.git
* libubus - git://nbd.name/luci2/ubus.git
* pkg-config
* uci

