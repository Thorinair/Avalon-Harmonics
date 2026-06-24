# Avalon Harmonics Puff

**Stereo multimode filter with Ping input**

Puff is a stereo multimode filter with a state variable circuit. The filter provides separate Low Pass, Band Pass and High Pass outputs for both channels, has an attenuvertable CV input, a V/OCT input, and a dedicated Ping input. The circuit has some interesting quirks in its design, resulting in some very gritty sounds in higher resonance levels. Note that the filter can't continuously self-oscillate. **Features a golden (ENIG coated) panel.**

The filter has two audio inputs for a left and right channel. For convenience, right channel is normalled to the left channel when nothing is plugged into it. Both left and right channels have separate LP, BP and HP outputs, allowing all three of the filter types to be used at the same time.

Filter circuit is based on Thomas Henry's VCF circuit, with some modifications and adjustments. Cutoff can be controlled with the CUT knob, and resonance with the RES knob. CUT knob's effective range is from around 9 o'clock to 3 o'clock, with the extra range being useful when combined with a CV signal for more aggressive cutoffs etc. Signal fed into the CV input jack can be attenuverted with the ATN knob, allowing for inverting of an envelope signal, an LFO, or whatever is plugged in. Cutoff can also be controlled with a 1V/OCT signal through the V/OCT jack. Frequency of the cutoff can be tuned, and the tuning trimmer is exposed on the front panel where the tuning fork icon is, just to the bottom-left of the CUT knob. A screwdriver can be used to adjust it.

Resonance on this filter is interesting, as it gets progressively more unstable in higher ranges. Above around 3 o'clock of the RES knob, standing wave-like peaks start appearing in certain frequencies of the cutoff, which correspond to the frequency of the signal fed into the filter. These peaks can get quite loud on high resonance levels, so this whole section of the knob is marked with a warning symbol. An IN GAIN knob is provided, which can be used to lower the input signal's level. A quieter input signal will result in quieter resonance peaks, allowing the peaks to be tamed to a managable level.

Lastly, the filter has a dedicated PING input jack. A gate, trigger, or even an LFO can be plugged into this jack to ping the filter. The circuit simply converts an incoming signal so that, above a certain threshold, it causes a short DC offset, effectively plucking the filter's resonance. Ping only really works in high resonance levels, so I suggest maxing out the RES knob for this application. One way to use it is to connect a V/OCT signal, as well as a gate signal of a sequencer, and directly play notes on the filter. LP, BP and HP outputs will all have a slightly different sound when being pinged, so there is a lot to explore! An LED next to the PING jack flashes on each ping.

**CALIBRATION:** V/OCT of the cutoff can be calibrated. All modules I build and ship come pre-calibrated, but there might be a slight difference depending on your power supply or some other factors like temperature. To calibrate Puff, set the RES knob to the max, keep the audio inputs unplugged, connect your keyboard or sequencer's V/OCT and GATE to Puff's V/OCT and PING, and start playing notes. I suggest using a proper tuner, some modules can do this, and there is also Korg's ST1K tuner. Calibration of Puff is very similar to any VCO, but you need to constantly send it gates or triggers to keep the tone going, as it can't continuously self-oscillate.

*How did the name "Puff" happen? I wanted a cute, silly and unique name. I played around in my head with multiple different ones like Fluff, Floof, Poof, Puff, but eventually ended up with Puff. Puff as in, apufferfish, a puffed up bird, etc!*

Visit Website: https://avalon-harmonics.com/module/Puff/

### Features

* Stereo multimode filter
* Separate LP, BP and HP outputs
* Attenuvertable CV input
* Tunable V/OCT input
* Dedicated Ping input
* Fully analog circuitry
* Wrong polarity protection
* Skiff friendly
* Size: 8HP
* Depth: 25mm
* Power: +12V: 35mA, -12V: 35mA

### Credits

* Filter circuit based on [Thomas Henry's VCF circuit](https://www.birthofasynth.com/Thomas_Henry/Pages/VCF-1.html)
* Tuning Fork Icon created by [Freepik - Flaticon](https://www.flaticon.com/free-icons/vibration)
* Alert Icon created by [Freepik - Flaticon](https://www.flaticon.com/free-icons/alert)
