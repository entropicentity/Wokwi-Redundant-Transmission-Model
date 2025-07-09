#Note

Due to limitations in the debugging capacity of Wokwi, an error persists upon running the gds runtime wherein the system insists that ther are undriven connections. This issue is entirely contained to the linter which insists certain wire nets are undriven, which cannot be rectified as wokwi wire nets are unnumbered so the flagged error message is meaningless. However, everything else functions exactly as it is supposed to, so this problem can safely be ignored.

#About

This is an signal redundancy system.

The two switches on the left, by the 
"Input Signal" text control the two bits
of data actually being transmitted, and you
can chech their state by the LED indicators
by the input green for bit 0 and blue for
bit 1.

The set of 6 switches at the top (the component has
8 but only 1-6 are used) controls
which of the intermediary wires face
distortion, which in this case is 
simulated by having that signal invert.
For these, off means no distortion on the
line and on means distortion on the line.

The signals then go into the logic system by
the text "Signal Recombination Logic" which
is able to correct for some distortion.

The resulting signal is then sent to the
two indicator LEDs by the text "Final
Received Signals" which are again green and 
blue.

the system can handle one line out of three
interfered with at a time without losing
signal integrity.
