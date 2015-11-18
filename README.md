uHTTPd
======

uHTTPd is a web server written from scratch by OpenWrt/LuCI developers. It is aimed towards being an efficient and stable server, suitable for lightweight tasks commonly used with embedded devices and proper integration with OpenWrt's configuration framework (UCI). In particular, it is configured by default for the LuCI web interface to administer OpenWrt. In addition, it provides all the functionality expected of present day web servers.

Compiling uHTTPd
----------------

On Ubuntu 14.04 LTS, uHTTPd requires:

* libjson0-dev
* libjson-c-dev
* liblua5.2-dev 
    sudo ln -s /usr/include/lua5.2/lua.h /usr/include/lua.h
    sudo ln -s /usr/include/lua5.2/luaxlib.h /usr/include/luaxlib.h
    sudo ln -s /usr/include/lua5.2/luaconf.h /usr/include/luaconf.h
    sudo ln -s /usr/include/lua5.2/lua.hpp /usr/include/lua.hpp
    sudo ln -s /usr/include/lua5.2/lualib.h /usr/include/lualib.h
* libubox
* libubus
* pkg-config
* uci

