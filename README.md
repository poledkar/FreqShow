FreqShow
========

Raspberry Pi &amp; PiTFT-based RTL-SDR frequency scanning and display tool.  See installation and usage instructions in the guide at:
https://learn.adafruit.com/freq-show-raspberry-pi-rtl-sdr-scanner/overview


## Changes in this fork
- Run with normal HDMI display (or on desktop PC, in Python virtual environment in `env` subdirectory).
- Show mouse cursor during (and shortly after) mouse activity.
- Accept input events again (likely broken by changes between `pygame 1` and `pygame 2`).
- Option to offset frequency by 125 MHz (when used with RF upconverter).
- Initial frequency changed from 90.3 MHz to 145 MHz.
- Terminate `pygame` properly (so that IDLE does not hang when app quits).
