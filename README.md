dwm
===

My patched version of suckless.org's dwm

Patches
-------

| Patch                                   | Description                                                                                 |
| --------------------------------------- | ------------------------------------------------------------------------------------------- |
| dwm-10e232f9ace7-pertag.diff            | different layouts per tag                                                                   |
| dwm-10e232f9ace7-swapfocus.diff         | reach the last used window via meta-s                                                       |
| dwm-6.0-monoclecount.diff               | replace the [M] with a count of how many windows there are and which one is currently shown |
| dwm-6.0-uselessgaps.diff                | choose in which modes there will be useless gaps between windows                            |
| dwm-r1615-mpdcontrol.diff               | control mpd via keyboard shorcuts                                                           |
| dwm-10e232f9ace7-push.diff              | move clients in the client list                                                             |
| dwm-6.0-deck.diff                       | add another layout in which the number of windows visible can be restricted                 |
| dwm-6.0-single\_window\_no\_border.diff | when in monocle mode, get rid of the border                                                 |
| dwm-6.1-systray.diff                    | add a system tray to the statusbar                                                          |

Compiling Instructions
----------------------

$ cd  
$ git clone git://github.com/jfucci/dwm.git && cd dwm  
edit config.h with your defaults (font, terminal, tags, etc), e.g.:  
$ vim config.h  
$ make  
$ sudo make install  
