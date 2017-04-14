# vnc2flv
Derived from http://www.unixuser.org/~euske/python/vnc2flv

vnc2flv is an excellent lightweight Python implementation of a VNC screen recorder. It outputs to the flv format, which can be easily converted to others (e.g. mp4) with ffmpeg. This derivative of vnc2flv includes functional CopyRect and Hextile support. No attempt was made to make this software robust to buffer overflow errors, etc, so use on an unprotected network at your own risk!

To install, run python setup.py install from the source directory. 

The systemd directory contains record.service and record.script, which are examples of how to use vnc2flv to setup automatic, continuous recording of a vnc session.
