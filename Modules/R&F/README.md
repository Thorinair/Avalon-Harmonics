# Avalon Harmonics R&F

**Dual slew limiter with independent rise and fall**

R&F is a dual slew limiter with a way of independently controlling the rise and fall of both channels.

Each slew limiter can have a slew speed from a very short one to a very long one. Since the curve of the slew limiting is linear, a larger jump in value will result in a longer slew period. The following slew times were measured when going from 0V to 5V and back:

* Slowest rise from 0V to 5V: ~7s
* Slowest fall from 5V to 0V: ~5s
* Fastest rise from 0V to 5V: ~4.6ms
* Fastest fall from 5V to 0V: ~2.7ms

The outputs have circuitry which mitigate voltage drop issues, allowing it to be used for slewing 1V/OCT signals as well. Additionally, both channels have a bipolar LED to monitor the output.

### Features

* Dual slew limiter
* Independent rise and fall speed
* Linear slew curve
* Status LEDs for output
* Wrong polarity protection
* Size: 3HP
* Depth: 41mm
* Power: +12V: 23mA, -12V: 23mA