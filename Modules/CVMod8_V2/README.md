# Avalon Harmonics CVMod8 V2

**8 channel CV attenuverter, offset and mixer**

CVMod8 V2 is successor to our old CVMod8. The module provides 8 channels of independent CV attenuverters and offset controls, as well as offset polarity switches and forward switches for mixing the channels together.

Each channel can be used as a static voltage source with the output available on the top-most row of jacks. Sliders control the voltage, and the voltage can be bipolar (+5V to -5V) or unipolar (+5V to 0V) by flipping the corresponding switch on the bottom. Behavior is bipolar when switched to the left and unipolar when switched to the right. Internally, voltage regulators ensure a precise voltage source. Note that there is a 5V spike when switching the polarity.

Each channel also has a signal input (second row of jacks) with a corresponding attenuverter knob below. The knobs have a centre detent as this is where the input gain is set to 0. When turned clockwise, level of the signal can be adjusted up to unity gain. When turned counter-clockwise, signal gets inverted up to a negative unity gain. The input signal is mixed together with the previously mentioned slider value, allowing the sliders to offset the incoming signal.

Output of each channel can be forwarded to the next channel by flipping a corresponding switch to the right in the upper row of switches. The signal is then mixed together with the attenuverted CV and offset of the next channel. Each channel has the following formula:

`output = input * attenuverter + offset + output_prev`

* `input` is whatever signal is plugged into the second row jack.
* `attenuverter` is the position of the attenuverter knob and can range from -1 to 1.
* `offset` is the offset voltage set by the slider and polarity switch. Can range from +5V to -5V or 5V to 0V.
* `output_prev` is the output signal from the previous channel, if the forwarding switch has been flipped.

The forwarding feature can be used to chain multiple channels together acting as a CV mixer with outputs still available on each channel. Plugging a cable into one of the outputs does not interrupt the forwarding, so it is possible to make use of submixes. If a need arises for an audio mixer, setting offsets to unipolar mode and sliding them all the way down will achieve this kind of behavior.

Lastly, a bipolar LED exists for each channel as a clear indicator of the status of the output voltage.

**Differences compared to the old CVMod8:**

* Attenuverters instead of normal attenuators, allowing for inverting signals.
* Easier finger access to the knobs as jacks are no longer in the way.
* More precise offset voltages using voltage regulators and buffering before mixing.
* Offset polarity toggles as accessible switches on the bottom.
* Forwarding of channels as accessible switches on the top.
* Visually a better fit of the slider knobs.
* For DIY-ers, easier to obtain slide pots and no more need for the 3D printed interface part.
* NOTE: More parts required the module to be around 10mm deeper and use more current.

Visit Website: https://avalon-harmonics.com/module/CVMod8_V2/

### Features

* 8 independent channels
* Offset for each channel with a polarity switch
* Each channel with an input and attenuverter
* Togglable forwarding of outputs to next channel
* Status LEDs for each channel
* Wrong polarity protection
* Size: 20HP
* Depth: 36mm
* Power: +12V: 123mA, -12V: 111mA