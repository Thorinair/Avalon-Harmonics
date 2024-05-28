# Avalon Harmonics VU

**Mono VU meter with envelope follower output**

**NOTE: This module is rather deep at 66mm without cable. Make sure to check if it fits in your case.**

VU is a highly compact mono VU meter and envelope follower. The VU display consists of 5 yellow, 3 orange, and 2 red LEDs. The module provides an input jack on the bottom, and a buffered output jack on top, allowing it to be placed right before the master output if so desired. Note that there is no AC coupling, so the module can also be used with slow moving CV signals if so desired.

VU meter can be in either bar or dot mode. This is selected by placing a jumper on the PCB. Leaving the jumper on puts the display in bar mode. The response curve of the VU display depends on the inserted LED driver chip. Three variants of the chip exist and are interchangable on the PCB. The compatible chips are:

* LM3914 - Linear response curve
* LM3915 - Logarithmic response curve, each LED is 3dB
* LM3916 - VU meter response curve, each LED corresponds to following dB levels: +3, +2, +1, 0, -1, -3, -5, -7, -10, -20

In order to drive the the VU display, the signal is first precision rectified, and then passed through an envelope follower. The falloff of this envelope can be adjusted using the HOLD knob, from virtually instantaneous falloff, to a few seconds long one. This envelope follower CV signal is also available on the PEAK output jack, and can be used to control any other module, for instance, to create a sidechain effect. Its voltage ranges from 0V to 9V, depending on the input signal and the set gain (see below).

In order to make the module compatible for different rack setups, a trimmer on the PCB (T_GAIN) allows you to adjust the internal gain of the envelope follower input. This allows you to adjust the VU meter so it hits the peak exactly when it would usually clip on the output module, or whatever is after it, ensuring a more accurate display. This gain does NOT affect the buffered output.

Lastly, the brightness of the last LED can be adjusted with a trimmer on the PCB (T_LED). The brightness can range from around same brightness like all other LEDs, to much brighter. Making the last LED brighter might be desireable to make the peak more visually obvious.

### Features

* Slim 2 HP design
* Buffered output jack
* Exchangable chips for the response curve
* Adjustable falloff speed
* Envelope follower CV output
* Low power use for the number of LEDs
* Wrong polarity protection
* Size: 2HP
* Depth: 66mm
* Power: +12V: 36mA, -12V: 15mA