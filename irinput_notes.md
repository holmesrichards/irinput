# IR Input notes

This modifies the Barton 078 IR Input module as follows:

* Added 3.5 mm TRS jack for a cable connecting to an external phototransistor. Switch to select internal or external PT. This allows using candles, lighters, etc. to control the synth while not having to have them right in front of it.
* Added gain knob to control gain of amplifier stage. The sensitivity pot (what Barton calls "bias") does vary the size of the signal but gives a small window between too small (no output) and too large (saturated). In AC coupled mode, the size of the AC component may be small, e.g. a few hundred mV, even when the sensitivity pot is set to just below saturation; of course the AC component disappears if the sensitivity pot is then raised. The gain pot may be used to amplify the AC component to the level of a few volts. In AC mode, the gain range is 1 to 11. In DC mode, the gain pot may be used to help with faint IR sources; the gain range is 1 to 2.
* Added a bicolor indicator LED for the CV output. Brightness is indicative of CV amplitude and color indicates sign (which is positive in DC mode but can go negative in AC mode). 
* Added an indicator LED for saturation. This turns on when the PT emitter voltage is about 10 V. Normally one would want to operate with the sensitivity pot adjusted to just below where this LED comes on continuously.
* Reversed the gate control pot, thinking of it as a threshold control (clockwise is higher threshold, slower gate rate) rather than a gate rate (clockwise is lower threshold, faster rate).
* Specified A1M rather than B1M for sensitivity pot.

