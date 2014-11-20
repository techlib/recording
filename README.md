# Multicast Video Recording Tool

This small [Twisted]()-based tool captures incoming UDP packets and forwards
them to `ffmpeg` for encoding and storage. After a period of inactivity
(when the camera is turned off) the recording is closed.

[Twisted-based]: https://twistedmatrix.com/trac/
