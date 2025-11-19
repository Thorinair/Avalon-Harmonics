# Avalon Harmonics Pulse

**Heartbeat to CV, gates and triggers**

Pulse is a module which links your heartbeat directly with your Eurorack setup by reading your pulse and converting it into usable CV signals, gates and triggers. You could drive your whole racks's BPM using your own heartbeat!

The sensor is worn on a finger and reads the body's pulse using a green LED PulseSensor. This signal is directly used to drive analog circuitry in the module. Status of the pulse can be monitored on the bipolar LED in the middle of the heart graphic on top of the module.

First set of available outputs are the CV value of the pulse, as well as an inverted CV value of the pulse. Both are available in the upper section of the module. LVL knob can be used to control the intensity of both of these outputs. Behavior of the outputs can change depending on how hard your heart is beating and how well the sensor is pressed against the skin. In normal operation, the outputs will behave like pulse shaped LFOs synced to the heartbeat.

Second set of outputs are the gates and triggers. Gates are generated using a threshold circuit. Using the THR knob, a threshold can be set which will cause a gate to happen when the pulse signal is above the threshold, and another gate when it is below. Each gate has a corresponding trigger output as well, and are generated automatically at the start of each gate. Left side of the module represents gates and triggers fired below the threshold, while right represents those above the threshold. Two LEDs above the THR knob also signify which gate is currently active.

**NOTE: It may take some experimentation to find the right spot on a finger for the sensor. A good spot will ensure a stable pulse with no dropouts. I found that it works best on the tip of my left index finger, near the bottom side of the knuckle. Your spot may be somewhere completely else.**


Visit Website: https://avalon-harmonics.com/module/Pulse/

### Features

* Heartbeat to CV, gates and triggers
* Status LED of the pulse
* CV level control
* Gate threshold adjustment
* Status LEDs for gates
* Wrong polarity protection
* Size: 4HP
* Depth: 36mm
* Power: +12V: 16mA, -12V: 10mA