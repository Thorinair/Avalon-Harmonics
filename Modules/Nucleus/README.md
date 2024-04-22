# Avalon Harmonics Nucleus

**Geiger counter random trigger and gate source**

**NOTE: Internals of this module are relatively high (111.1 mm) and installing it could be problematic on some Eurorack modular racks, but it fits without a problem inside mine. Please make sure you have enough vertical space between the rails before buying.**

Nucleus is the module which sparked the start of Avalon Harmonics modules. It is a Geiger counter powered trigger and gate randomizer. The Geiger-Müller tube can be accessed through an alcove in the upper section of the module, allowing a radioactive sample to be placed, but module produces decent clicks even with just background radiation. An LED inside the alcove illuminates the tube for added effect.

On each Geiger counter click, the module generates a trigger output, which is available on the corresponding jack connector. The length of the trigger can be adjusted using a trimmer on the back PCB to make the module better suited for each modular system.

Triggers also stimulate the gate output, setting it to high after a trigger has happened. The length of the gate can be adjusted using the large knob in the center: from a very short duration, up to around 5 seconds. Each subsequent trigger will prolong the duration of the gate. An inverted gate output is available as well, providing a high signal when the gate is low.

All outputs can be completely disabled by flipping the switch. This keeps the Geiger counter running but disables all outputs. If there is any ongoing gate, it will not be immediately interrupted by flipping the switch.

Lastly, there is an LED on the input next to the tube alcove, signifying Geiger counter clicks. Two more LEDs are placed above the trigger output and gate output to allow for monitoring of the outputs.

### Features

* Geiger counter randomizer
* Accessible Geiger-Müller tube
* Randomized trigger output
* Randomized gate output
* Gate duration knob
* Inverted gate output
* Wrong polarity protection
* Size: 8HP
* Depth: 56mm
* Power: +12V: 11mA, -12V: 0mA

**DISCLAIMER: Geiger-Müller tube is charged to around 400V on its anode. For your protection, these high voltage parts of the circuit are hidden inside a 3D printed enclosure and are not easily accessible. Opening the enclosure could expose you to these voltages even when the module is turned off due to a charge in the capacitors. Open only at your own risk!**