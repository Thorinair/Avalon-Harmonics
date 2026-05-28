# Avalon Harmonics CVModH

**2 channel CV attenuverter, offset and mixer in 1U format**

CVModH is functionally identical to the Avalon Harmonics CVMod4 and CVMod8 V2, but provides 2 channels and is designed to be used in a 1U row. The whole layout has been adjusted to make it horizontal, while preserving what makes other CVMod modules useful. This module is a perfect match with the Avalon Harmonics MiniDJ, expanding the original knobs to sliders instead. **Features a golden (ENIG coated) panel.**

The module provides 2 channels of independent CV attenuverters and offset controls, as well as offset polarity switches and a forward switch for mixing the channels together.

Each channel can be used as a static voltage source with the output available on the right-most column of jacks. Sliders control the voltage, and the voltage can be bipolar (+5V to -5V) or unipolar (+5V to 0V) by flipping the corresponding switch on the bottom. Behavior is bipolar when switched to the top and unipolar when switched to the bottom. Internally, voltage regulators ensure a precise voltage source. Note that there is a 5V spike when switching the polarity.

Each channel also has a signal input (left column of jacks) with a corresponding attenuverter knob to the left. The knobs have a centre detent as this is where the input gain is set to 0. When turned clockwise, level of the signal can be adjusted up to unity gain. When turned counter-clockwise, signal gets inverted up to a negative unity gain. The input signal is mixed together with the previously mentioned slider value, allowing the sliders to offset the incoming signal.

Output of first channel can be forwarded to the second channel by flipping the middle switch to the bottom. The signal is then mixed together with the attenuverted CV and offset of the second channel. Each channel has the following formula:

`output = input * attenuverter + offset + output_prev`

* `input` is whatever signal is plugged into the left column jack.
* `attenuverter` is the position of the attenuverter knob and can range from -1 to 1.
* `offset` is the offset voltage set by the slider and polarity switch. Can range from +5V to -5V or 5V to 0V.
* `output_prev` is the output signal from the previous channel, if the forwarding switch has been flipped.

The forwarding feature can be used to combine the two channels together acting as a CV mixer with outputs still available on each channel. Plugging a cable into one of the outputs does not interrupt the forwarding, so it is possible to make use of submixes. If a need arises for an audio mixer, setting offsets to unipolar mode and sliding them all the way down will achieve this kind of behavior.

Lastly, a bipolar LED exists for each channel as a clear indicator of the status of the output voltage.

Visit Website: https://avalon-harmonics.com/module/CVModH/

### Features

* 2 independent channels
* Offset for both channels with a polarity switch
* Both channels with an input and attenuverter
* Togglable forwarding of output to second channel
* Status LEDs for both channels
* Wrong polarity protection
* Skiff friendly
* Size: 22HP 1U
* Depth: 25mm
* Power: +12V: 28mA, -12V: 25mA