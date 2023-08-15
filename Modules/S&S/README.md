# Avalon Harmonics S&S

**S&H with built in random, slew limiter and noise source**

S&S is a complex module which offers multiple features in a tight 3hp package.

In its core, it is a sample & hold module with standard input and trigger jacks. The input that can be sampled and can range from around 10V to -4.5V. If the value is outside this range, it will be clipped but won't damage the module. Note that the sampled value will slowly drop down with time towards around -6V, so if sampling 1V/OCT, it is best to use it for shorter notes.

It can also perform sampling from a built in random source. This allows it to be used as a randomizer. The random source generally generates values between -2.5V and +2.5V, but can randomly assume any value within the sampleable range. Note that in this mode, the module will default to -6V when turned on for the first time. Source of the sampled values can be chosen with the top-most switch.

Sampling speed can go all the way into high audio rates, allowing the module to be used as a sort of sample crusher effect. For slower sample rates, the held value can be slew limited by engaging the second switch. After enabling, the knob controls the slew time, from very short to quite long. This can be useful to smooth out the output and serve as a continuous random CV modulator.

The module also has an extra white noise output jack. This noise is internally used for the S&H random source, but may also be used here for drum synthesis or such.

Lastly a bipolar LED shows the status of the output of the module.

### Features

* S&H with multiple extra features
* Sample from CV or random
* Sample high audio rates
* Optional slew limiting of the held value
* Extra white noise output
* Status LED for output
* Wrong polarity protection
* Size: 3HP
* Depth: 56mm
* Power: +12V: 21mA, -12V: 19mA