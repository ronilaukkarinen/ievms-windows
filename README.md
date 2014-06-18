ievms-windows
=============

This is an automated script for Microsoft modern.IE Virtualization Tools for Virtualbox for Windows. There are already automated ways for building ievms for Mac OS X and Linux, but not really for Windows PC. It's a pain to download every executable by hand because the files are so massive and you get old waiting so that's why I created this simple script to help with the process.

The script is for Internet Explorers versions IE7-11. IE6 is already dead and it's not fun to look at.

Requirements
----

 - Oracle VM VirtualBox for Windows: https://www.virtualbox.org/wiki/Downloads
 - GNUWin32 wget for Windows: http://gnuwin32.sourceforge.net/packages/wget.htm

Usage
----

1. Set PATH (Computer > Properties > Advanced System Settings > Environment Variables > System Variables > Path > Variable value: add `;C:\Program Files (x86)\GnuWin32\bin` in the end of input.
2. Run ievms_windows.bat