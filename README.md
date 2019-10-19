A 8-bit wallpaper collection for GNOME
=========

Installation from Git Source
------------

1. Check build-requirements:

 ```
 * libglib2.0-dev (glib2)          >= 2.48.0
 * meson                           >= 0.40
 ```

2. Build and install system-wide:

 ```
 meson build --prefix=/usr && cd build
 ninja
 sudo ninja install
 ```
