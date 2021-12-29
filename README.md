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
- Shorter bootstrap delay, inspired by [@rgtokett](https://github.com/rgrokett/FreqShow/commit/0d6f4e59d2acaaba66606fba6a0d76d05b08c759).

## Further inspiration to explore
- https://github.com/edmondhk/FreqShow for peak hold line, offset of intensity, runnable `.py`.
- https://github.com/estradjm/FreqShow_USRP for command line arguments.
- https://github.com/gloutsch/FreqShow for windowed (desktop) mode, palette in waterfall.
- https://github.com/kieransimkin/FreqShow for "drastic improvement of waterfall perfomance".
- https://github.com/mtippett/FreqShow for keyboard handling.
- https://github.com/rgerganov/FreqShow for UI changes, recording.
- https://github.com/rgrokett/FreqShow for smooth curve, grid background.
- https://github.com/drewby08/FreqShow for FM demodulation.
