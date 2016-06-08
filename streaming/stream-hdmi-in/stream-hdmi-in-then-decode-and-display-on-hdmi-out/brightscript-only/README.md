# streaming/stream-hdmi-in/stream-hdmi-in-then-decode-and-display-on-hdmi-out/brightscript-only
This script creates a multicast stream from the HDMI input on a BrightSign player. 
Any device or PC on the local network that can accept a UDP stream can receive and play this stream.
In addition, the script decodes the stream and plays it back on the local HDMI output.
All encoding and decoding is done in BrightScript.
To run this sample, put all files in this folder on an SD card, insert it in a BrightSign player, and reboot. 

Notes:
- This requires a BrightSign model that has an HDMI input
- You can only stream non-encrypted content. If you attempt to stream, for example, the output of a DVD player, it will be disallowed
