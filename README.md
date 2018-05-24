# NvIndicator #

![NvIndicator Screenshot](https://raw.githubusercontent.com/jytou/nvindicator/master/screenshot.png)

_NvIndicator_ is an NVIDIA GPU indicator applet for Unity

## Notes ##

This is a modified version of the original, it works with more than one graphics card (this functionality was broken somehow) and shows only the temperature an the GPU usage % in the taskbar, all other indicators are shown in the drop down menu as in the other version.

I have also added a simple desktop file so that the indicators will start automatically on startup. For this to work, you have to put a link in /usr/bin/nvindicator to the nvindicator.py file where you have checked out this repository.
