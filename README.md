dwm
===

My patched version of suckless.org's dwm

Patches
-------

dwm-6.0-focusonclick - focus a window on click instead of on hover  
dwm-6.0-pango        - Xft fonts  
dwm-6.0-pertag       - allow each tag to have a different layout  
dwm-6.0-push         - push windows in the stack  
dwm-6.0-systray      - adds a system tray in the right of the status bar  
dwm-r1606-exresize   - adds resize features (remember floating windows' positions, resize with the keyboard)  

Compiling Instructions
----------------------

$ cd  
$ git clone git://github.com/jfucci/dwm.git && cd dwm  
edit config.h with your defaults (font, terminal, tags, etc), e.g.:  
$ vim config.h  
$ make  
$ sudo make install  
