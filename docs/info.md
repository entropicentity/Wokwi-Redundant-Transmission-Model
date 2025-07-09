<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The two switches on the left, by the "Input Signal" text control the two bits of data actually being transmitted, and you can chech their state by the LED indicators by the input green for bit 0 and blue for bit 1.

The set of 6 switches at the top (the component has 8 but only 1-6 are used) controls which of the intermediary wires face distortion, which in this case is  simulated by having that signal invert. For these, off means no distortion on the line and on means distortion on the line.

The signals then go into the logic system by the text "Signal Recombination Logic" which is able to correct for some distortion.

The resulting signal is then sent to the two indicator LEDs by the text "Final Received Signals" which are again green and blue.

the system can handle one line out of three interfered with at a time without losing signal integrity.

## How to test

To test, switch any given distortion switch at the top to on, and then switch the two input switches, see that as long as each set of 3 wires, the green and blue, only have one line with distortion, that the output and input indicator lights are always the same, indicating bit integrity despite the distortion of the bit on one of the three lines.

## External hardware

Colored LEDs: 2 green, 2 blue; 2 Slide Switch.
