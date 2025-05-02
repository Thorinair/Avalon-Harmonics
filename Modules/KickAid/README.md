# Avalon Harmonics KickAid

**Kick rumble helper for ducking, EQing and mixing**

KickAid is a module designed to help with various stages of processing kick rumble. It helps with amplifying an external kick instrument, automatically detecting the kick, performing ducking on a reverb from a send and return, equalizing the kick and rumble, and mixing them together. Note that the module still requires a kick source and a module that can provide the reverb effect.

Firstly, a kick source should be connected to the IN jack. Module can accept either a Eurorack level kick or one from an external instrument. The up-most GAIN knob can be used to amplify the incoming signal up to 17 times if necessary. Amplified kick is then sent to the SEND jack, which should be connected to a reverb module of choice. Output of the reverb module should be connected back to the RTRN jack.

Once these connections are achieved, module can be used for its intended purpose: creating kick rumble. Kicks will stimulate a ducking effect on the reverb signal and thus create a sidechain effect. Both kick and rumble can be tilt-equalized separately using the EQ KICK and EQ FX knobs. The two signals can then be crossfaded using the MIX knob in the center. Final output is available on the OUT jack. Note that the output is AC coupled so it can only be used for audio signals.

The module allows for very fine control of the ducking behavior using six potentiometers and a switch, as well as monitoring of the behavior using four LEDs.

To achieve the ducking, the following processing chain is performed:

1. The kick is first rectified with the status visible on the K LED.
2. The rectified signal is then passed through an envelope follower, and the result is visible on the F LED. Smoothing of the follower can be adjusted using the FALL pot. The follower can be overriden with an external signal by plugging a cable into the EXT jack.
3. The output is then passed through a thresholding circuit. Using the THRS pot, a trigger and gate signal is generated when the value is above the set threshold, with the gate shown on the G LED. Outputs of the trigger and gate are also available on the TRIG and GATE jacks. Behavior of the gate can be changed using the switch in the middle. When set to the left, gete is open when the value is above the threshold. When set to the right, the gate will have a static length set by the LENG pot.
4. Finally, the gate is inverted and used to generate a ducking envelope. Attack can be set using the ATCK pot and decay using the DECY pot. Intensity of the ducking can be adjusted using the DUCK pot. Status is visible on the E LED. This envelope is used to duck the rumble, and is also available as an envelope on the ENV jack.

The module's primary purpose is for creating kick rumble, but can also be used for various other things. For instance, it can be used to duck basslines against a kick simply by plugging the bassline into the RTRN jack. Or it can be used to create big reverbs which fade in after a synth lead. The TRIG output can also be used to drive the clock of the rack based on a four-on-the-floor kick beat coming from an external instrument. The possibilities are only limited by the creativity of the operator!

Visit Website: https://avalon-harmonics.com/module/KickAid/

### Features

* Kick rumble processor with tons of features
* External amplification up to 17 times
* Kick and rumble equalization
* Kick and rumble mixing
* Kick detection with trigger and gate outputs
* Ducking envelope generator with envelope output
* LED monitoring of the envelope stages
* Usable for things beyond just kicks
* Wrong polarity protection
* Size: 8HP
* Depth: 36mm
* Power: +12V: 46mA, -12V: 41mA